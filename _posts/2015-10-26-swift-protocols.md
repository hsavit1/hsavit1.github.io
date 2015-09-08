---
layout: post
title:  "Playing with Swift Protocols"
date:   2015-10-26 20:20:15
comments: true
---

There's a heck of a lot to know about Protocols in the Swift language - they're the glue that binds the entire thing together. In this post I'll do my best to explore the insane topics of Swift Collection Protocols, Comparison Protocols, Default Protocols and Protocol Oriented Programming. Big shoutout to NSHipster for all of their work on these subjects

#Collection Protocols
- Equitable
- Comparable
- Hashable

#Comparison Protocols
- SequenceType / GeneratorType
- CollectionType / MutableCollectionType
- Sliceable / MutableSliceable
- ExtensibleCollectionType / RangeReplaceableCollectionType

A collection (a type that conforms to the next collection protocol, CollectionType) is a step beyond a sequence in that individual elements of a collection can be accessed multiple times via subscript.

Sliceable collections promise efficient slicing of a subrange of a collection's elements. That is, getting a slice of a collection should not require allocating new memory for the selected elements

Collections that conform to ExtensibleCollectionType and RangeReplaceableCollectionType provide methods to modify the collection.

#Default Protocols
Generics are the defining feature of Swift. Working in coordination with the language's powerful type system, a developer can write safer and more performant code than was ever possible with Objective-C.
The underlying mechanism for generics are protocols. A Swift protocol, like an Objective-C @protocol declares methods and properties to be implemented in order to conform to it.

"Within the Object-Oriented paradigm, types are often conflated with class identity. When programming in Swift, though, think about polymorphism through protocols first, before resorting to inheritance."

The one major shortcoming of protocols, both in Swift and Objective-C, is the lack of a built-in way to provide default implementations for methods, as one might accomplish in other languages with mixins or traits.

...but that's not the end of the story. Swift is a fair bit more Aspect-Oriented than it initially lets on.


#Protocol Oriented Programming
