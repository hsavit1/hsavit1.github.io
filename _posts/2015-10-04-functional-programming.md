---
layout: post
title:  "Functional Programmng Patterns in Scala and Clojure"
date:   2015-10-04 17:20:15
comments: true
---

Recently I've jumped into some advanced functional programming topics. This latest topic was a look into functional programming with Scala and Clojure

> Some OO Patterns to be Dumped

1. State Carrying Functional Interface
2. Command
3. Builder for Immutable Object
4. Iterator
5. Template Method
6. Strategy
7. Null Object
8. Decorator
9. Visitor
10. Dependency Injection

> Some New Functional Patterns

1. Mutual Recursion
2. Filter-Map-Reduce
3. Chain of Operations
4. Function Builder
5. Memoization
6. Lazy Sequence
7. Focused Mutability
8. Customized Control Flow
9. Domain Specific Language



Also see the "Purely Functional Data Structures" written in 1996 by some guy named Okasaki or something. He defines quite a few. Here's some more since that book was made. From this [link](http://cstheory.stackexchange.com/questions/1539/whats-new-in-purely-functional-data-structures-since-okasaki/1550#1550)

Here's the book [Link](http://www.cs.cmu.edu/~rwh/theses/okasaki.pdf)

1. Ideal Hash Trees
2. Functional Priority Search Queues
3. One sided flexible arrays
4. Catenable sets
5. Maxiphobic heaps
6. Catenable Sorted Lists
7. Confluently Persistent Tries
8. Functional Delete Algorithm for Red Black Trees
9. RGB Trees: Effcient Immutable Vectors
10. Zipper
11. Braun Trees
12. Biased Search Trees
13. Finger Trees


> FP has a strong linguistic and cultural preference for algebraic composition at every layer (e.g. algebraic data types, functions, functors, categories, monads, machines, monoids, lenses, signal functions, algebraic effects). Purity makes it relatively easy to capture multiple views of a system, or to view an external state in many ways.  Functions over data are a lot simpler than event patterns.  Functions are relatively easy to test in isolation or reuse in a new context.
