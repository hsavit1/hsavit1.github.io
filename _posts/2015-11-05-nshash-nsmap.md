---
layout: post
title:  "A look at a long list of data structures in ObjC"
date:   2015-11-05 15:20:15
comments: true
---

`NSSet` and `NSDictionary` are fantastic and can be used 99% of the time. However, in the situations where memory management constraints are a concern, `NSHashTable` and `NSMapTable` are worth a look

###NSHashTable
Unlike it's analouge `NSSet`, `NSHashTable` holds `weak` references to its members. It can also contain arbitary pointers, and user pointer identity for equality checks and hashing checks

	NSHashTable *hashTable = [NSHashTable hashTableWithOptions:NSPointerFunctionsCopyIn];
	[hashTable addObject:@"foo"];
	[hashTable addObject:@"bar"];
	[hashTable removeObject:@"bar"];
   	NSLog(@"Members: %@", [hashTable allObjects]);

See that line of code `NSPointerFunctionsCopyIn` ? 
- NSHashTableStrongMemory
- NSHashTableWeakMemory
- NSHashTableZeroingWeakMemory
- NSHashTableCopyIn
- NSHashTableObjectPointerPersonality

##NSMapTable
Like `NSHashTable`, in that it holds `weak` refs to it's members, unlike it's analouge NSDictionary and NSMutableDictionary. When a key or a value is removed from an `NSMapTable`, the entire reference will be removed. Additionally, `NSMapTable` can copy it's values on input and it can contain arbitary pointers - meaning it can use pointer identity for equality / hashing checks. Consider using `NSMapTable` in situations where keys are non-copyable, or if you want to store weak references to keyed delegates or some other kind of weak object

```objective-c
id delegate = ...;
NSMapTable *mapTable = [NSMapTable mapTableWithKeyOptions:NSMapTableStrongMemory
                                             valueOptions:NSMapTableWeakMemory];
[mapTable setObject:delegate forKey:@"foo"];
NSLog(@"Keys: %@", [[mapTable keyEnumerator] allObjects]);
```

Object subscripting was the new notation introduced in Clang 3.1 / ObjC-2.0 with along with all the new literal syntax

```objective-c
dictionary[@"foo"] = @42;
array[0] = @"bar"
```

If you want to do object subscripting in NSMapTable, add it in a category. Just add these 2 methods

```objective-c
- (id)objectForKeyedSubscript:(id)key	{
	return [self objectForKey:key];
}

- (void)setObject:(id)obj forKeyedSubscript:(id)key	{
	[self setObject:obj forKey:key];
}
```

`NSMapTable` has 4 conveience constructors:
- strongToStrongObjectsMapTable
- weakToStrongObjectsMapTable
- strongToWeakObjectsMapTable
- weakToWeakObjectsMapTable

If you’re wondering why Apple “forgot” adding subscripting to `NSMapTable`, you now know why. Subscripting requires an `id<NSCopying>` as key, which is not necessary for `NSMapTable`. There’s no way to add subscripting to it without having an invalid API contract or weakening subscripting globally with removing the `NSCopying` protocol.

##NSCache
NSCache is quite an odd collection. Added in iOS 4 / Snow Leopard, it’s mutable by default, and also thread safe. This makes it perfect to cache objects that are expensive to create.  It automatically reacts to memory warnings and will clean itself up based on a configurable “cost.” In contrast to NSDictionary, keys are retained and not copied.

#NSIndexSet
 It can save a collection of unsigned integers in a very efficient way, especially if it’s only one or a few ranges. As the name “set” already implies, each NSUInteger is either in the index set or isn’t. If you need to store an arbitrary number of integers that are not unique, better use an NSArray.