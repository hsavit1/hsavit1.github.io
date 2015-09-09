---
layout: post
title:  "SequenceType and GeneratorType"
date:   2015-09-05 17:20:15
comments: true
---

#Sequences, Generators, and Collections

Swift has a well-designed and expansive suite of built-in collection types. Beyond Array, Dictionary, and the brand new Set types, the standard library provides slices, lazy collections, repeated sequences, and more, all with a consistent interface and syntax for operations. A group of built-in collection protocols—SequenceType, CollectionType, and several others—act like the steps on a ladder. With each step up, a collection type gains more functionality within the language and the standard library. By conforming to these protocols, custom collection types can gain access to the same language constructs and powerful top-level functions we use with Array and Dictionary.

A `sequence` (a type that conforms to SequenceType ) represents a series of values, while a `generator` (conforming to GeneratorType, of course) provides a way to use the values in a sequence, one at a time, in sequential order. 

In short, a `generator` encodes the knowledge to produce new values. A `sequence` encodes how to create a generator. A `collection` adds random access to that.

The `SequenceType` protocol only has one requirement: every `sequence` must provide a `generator` from its `generate()` method.

A `generator` works by providing a single method, namely, `next()`, which simply returns the next value from the underlying sequence. next() will continue returning values until there are none left (), at which point it will return nil. Note that this may never comes to pass, since sequences aren't necessarily finite.

The relationship between the two protocols is asymmetrical. That is, every sequence has a generator, but only some generators are themselves also sequences (which they can become by returning themselves from their `generate()` method)

	protocol GeneratorType {
	    typealias Element
	    mutating func next() -> Element?
	}

`GeneratorType` defines a function `next()`, which returns an optional value of element. Whenever you have a value that conforms to the `GeneratorType`, you can keep calling next() until you get a nil value. 	

All the generators above can be iterated over exactly once. If we want to iterate again, we have to create a new value. This is also encoded in the definition: they are classes, and not structs. They don't get copied when shared, but rather, get passed by reference.

Because iterating multiple times is very common, there is `SequenceType`. The `SequenceType` protocol builds on top of `GeneratorType`. It asks us to specify the type of the generator, and a function that creates a new generator.  The typealias definition in the protocol means that, in order to conform to the protocol, we need to specify a type as well (either explicitly, with a typealias, or implicitly).

	protocol SequenceType {
	    typealias Generator: GeneratorType
	    func generate() -> Generator
	}

A collection builds on top of a sequence, and adds repeatable iteration and access to the elements via an index.

- Want to iterate over the collection? for x in collection.
- Want to iterate over all the indices of a collection? for idx in collection.indices.
- Want to number all the elements in a collection? for (num,element) in collection.enumerate().
- Want to find a specific element in a collection? if let idx = collection.indexOf({ someMatchingLogic($0) }).
- Want to transform all the elements in a collection? array.map { someTransformation($0) }.
- Want to fetch only the elements matching a specific criteria? collection.filter { someCriteria($0) }.