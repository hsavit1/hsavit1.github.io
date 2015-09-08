---
layout: post
title:  "Eqality in Objective C"
date:   2015-09-05 20:20:15
comments: true
---

Equality in Objective-C can get a little bit obnoxious if you don't know what you're doing. 

Let's make a distiction first: Two objects may be equal or equivalent to one another, if they share a common set of observable properties. Yet, those two objects may still be thought to be distinct, each with their own identity. In programming, an object's `identity` is tied to its memory address.

NSObject tests equality with another object with the method isEqual:. In its base implementation, an equality check is essentially a test for identity. Two NSObjects are considered equal if they point to the same memory address.

	@implementation NSObject (Approximate)
	- (BOOL)isEqual:(id)object {
	  return self == object;
	}
	@end
	
For container classes like NSArray, NSDictionary, and NSString, the expected and indeed more useful behavior would be to do a deep equality comparison, to test that each member in the collection is equal.

Subclasses of NSObject implementing their own `isEqual:` method are expected to do the following:

- Implement a new `isEqualTo__ClassName__:` method, which performs the meaningful value comparison.
- Override `isEqual:` to make class and object identity checks, falling back on the aforementioned value comparison method.
- Override `hash` 

The following NSObject subclasses in Foundation have custom equality implementations, with the corresponding method:

- NSAttributedString -isEqualToAttributedString:
- NSData -isEqualToData:
- NSDate -isEqualToDate:
- NSDictionary -isEqualToDictionary:
- NSHashTable -isEqualToHashTable:
- NSIndexSet -isEqualToIndexSet:
- NSNumber -isEqualToNumber:
- NSOrderedSet -isEqualToOrderedSet:
- NSSet -isEqualToSet:
- NSString -isEqualToString:
- NSTimeZone -isEqualToTimeZone:
- NSValue -isEqualToValue:

When comparing two instances of any of these classes, one is encouraged to use these high-level methods rather than `isEqual:`.

-----

What is a `hash:`? Let's go back to our computer science 101 days to recollect

A **hash table** is a fundamental data structure in programming, and it's what enables NSSet & NSDictionary to have fast (O(1)) lookup of elements.

We can best understand hash tables by contrasting them to arrays:

**Arrays** store elements in sequential indexes, such that an Array of size n will have slots at positions 0, 1, up to n - 1. To determine where an element is stored in the array (if at all), each position would have to be checked one-by-one (unless the array happens to be sorted, but that's another story).

**Hash Tables** take a slightly different approach. Rather than storing elements sequentially (0, 1, ..., n-1), a hash table allocates n positions in memory, and uses a function to calculate a position within that range. A hash function is deterministic, and a good hash function generates values in a relatively uniform distribution without being too computationally expensive. A hash collision occurs when two different objects calculate the same hash value. When this happens, the hash table will seek from the point of collision and place the new object in the first available place. As a hash table becomes more congested, the likelihood of collision increases, which leads to more time spent looking for a free space (hence why a hash function with a uniform distribution is so desireable).

