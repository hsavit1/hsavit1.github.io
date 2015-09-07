---
layout: post
title:  "NSHashTable and NSMapTable"
date:   2015-11-05 15:20:15
comments: true
---

NSSet and NSDictionary are fantastic and can be used 99% of the time. However, in the situations where memory management constraints are a concern, NSHashTable and NSMapTable are worth a look

###NSHashTable
Unlike it's analouge NSSet, NSHashTable holds `weak` references to its members. It can also contain arbitary pointers, and user pointer identity for equality checks and hashing checks

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
Like NSHashTable, in that it holds `weak` refs to it's members, unlike it's analouge NSDictionary and NSMutableDictionary. When a key or a value is removed from an NSMapTable, the entire reference will be removed. Additionally, NSMapTable can copy it's values on input and it can contain arbitary pointers - meaning it can use pointer identity for equality / hashing checks. Consider using NSMapTable in situations where keys are non-copyable, or if you want to store weak references to keyed delegates or some other kind of weak object

	id delegate = ...;
	NSMapTable *mapTable = [NSMapTable mapTableWithKeyOptions:NSMapTableStrongMemory
	                                             valueOptions:NSMapTableWeakMemory];
	[mapTable setObject:delegate forKey:@"foo"];
	NSLog(@"Keys: %@", [[mapTable keyEnumerator] allObjects]);


Object subscripting was the new notation introduced in Clang 3.1 / ObjC-2.0 with along with all the new literal syntax

	dictionary[@"foo"] = @42;
	array[0] = @"bar"

If you want to do object subscripting in NSMapTable, add it in a category. Just add these 2 methods

	- (id)objectForKeyedSubscript:(id)key	{
		return [self objectForKey:key];
	}
	
	- (void)setObject:(id)obj forKeyedSubscript:(id)key	{
		[self setObject:obj forKey:key];
	}
