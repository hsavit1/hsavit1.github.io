---
layout: post
title:  "SequenceType and GeneratorType"
date:   2015-09-05 17:20:15
comments: true
---

Swift has a well-designed and expansive suite of built-in collection types. Beyond Array, Dictionary, and the brand new Set types, the standard library provides slices, lazy collections, repeated sequences, and more, all with a consistent interface and syntax for operations. A group of built-in collection protocols—SequenceType, CollectionType, and several others—act like the steps on a ladder. With each step up, a collection type gains more functionality within the language and the standard library. By conforming to these protocols, custom collection types can gain access to the same language constructs and powerful top-level functions we use with Array and Dictionary.

A `sequence` (a type that conforms to SequenceType ) represents a series of values, while a `generator` (conforming to GeneratorType, of course) provides a way to use the values in a sequence, one at a time, in sequential order. 

The SequenceType protocol only has one requirement: every sequence must provide a generator from its generate() method.

A generator works by providing a single method, namely, next(), which simply returns the next value from the underlying sequence. next() will continue returning values until there are none left (), at which point it will return nil. Note that this may never comes to pass, since sequences aren't necessarily finite.

The relationship between the two protocols is asymmetrical. That is, every sequence has a generator, but only some generators are themselves also sequences (which they can become by returning themselves from their generate() method)