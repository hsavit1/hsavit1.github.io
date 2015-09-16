---
layout: post
title:  "Essential Algorithms (book)"
date:   2015-10-10 17:20:15
comments: true
---

#My attempt to break down this amazing book, chapter by chapter

1. Algorithm Basics
2. Numerical Algorithms
3. Linked Lists
4. Arrays
5. Stacks and Queues
6. Sorting
7. Searching
8. Hash Tables
9. Recursion
10. Trees 
11. Balanced Trees
12. Decision Trees
13. Basic Network Algorithms
14. More Netowrk Algorithms
15. String Algorithms
16. Cryptography
17. Complexity 
18. Distributed Algortihms 
19. Interview Puzzles


###1. Algorithm Basics
An algorithm is a recipe for performing a certain task. A data structure is a way of arranging data to make solving a particular problem easier

Know your Big-O Notation when figuring out an algorithm. The chapter defines 5 rules for Big-O notation:
1. “If an algorithm performs a certain sequence of steps f(N) times for a mathematical function f, it takes O(f(N)) steps.”
2. “If an algorithm performs an operation that takes O(f(N)) steps and then performs a second operation that takes O(g(N)) steps for functions f and g, the algorithm's total performance is O(f(N) + g(N)).”
3. “If an algorithm takes O(f(N) + g(N)) and the function f(N) is greater than g(N) for large N, the algorithm's performance can be simplified to O(f(N)).”
4. “If an algorithm performs an operation that takes O(f(N)) steps, and for every step in that operation it performs another O(g(N)) steps, the algorithm's total performance is O(f(N) + g(N)).”
5. “Ignore constant multiples. If C is a constant, O(C × f(N)) is the same as O(f(N)), and O(f(C × N)) is the same as O(f(N)).”

###2. Numerical Algorithms
Numerical algorithms calculate numbers. They perform such tasks as randomizing values, breaking numbers into their prime factors, finding greatest common divisors, and computing geometric areas.
All these algorithms are useful occasionally, but they also demonstrate useful algorithmic techniques such as adaptive algorithms, Monte Carlo simulation, and using tables to store intermediate results 

- Randomizing Data: By "randomizing data," the book mean seeing how a program would fare with any random input. A great example of this is a Monte Carlo simulation. It's actually hard to get truly random values (hisenberg's uncertainity principle and quantum mechanics confirm that). We use a process called a _liner congruential generator_ to generate random values and are mostly satified that the values are random enough.
- Finding Greatest Common Divisors: Use Euclid's Algorithm, it's pretty fast!
- Working with Prime Numbers: Prime numbers play important roles in some applications where their special properties make certain operations easier or more difficult. For example, some kinds of cryptography use the product of two large primes to provide security. The fact that it is hard to factor a number that is the product of two large primes is what makes the algorithm secure.
- Performing Numerical Integration: Monte Carlo integration is form of numeric integration in which the program generates a series of pseudorandom points uniformly within an area and determines whether each point lies within the target region”
- Finding Zeros: Sometimes a program needs to figure out where an equation crosses the x-axis. In other words, given an equation y = f(x), you may want to find x where f(x) = 0. Values such as this are called the equation's roots.
- Summary: This chapter explained the ideas of fairness and bias, two very important concepts for any sort of randomized algorithm, such as the Monte Carlo integration algorithm, which also was described in this chapter. This idea of making a program adapt to spend the most time on the most important parts of the problem is applicable to many algorithms. Many numerical algorithms, such as GCD, Fermat's primality test, the rectangle and trapezoid rules, and Monte Carlo integration, don't need complex data structures. In contrast, most of the other algorithms described in this book do require specialized data structures to produce their results 

###3. Linked Lists
Linked lists are probably the simplest data structures you'll build. However, some of the concepts you use to build them are also used to build the most sophisticated data structures described in this book. To use a linked list, you need to understand cells and links in addition to methods of finding, inserting, and deleting cells. You use those same concepts to build complicated networks, trees, and balanced trees, which can be confusing.
A linked list is built of objects that are often called cells. The cell's class contains whatever data the list must store plus a link to another cell. The link is simply a reference or pointer to another object of a cell's class. Often the pointer field in the cell class is called Next.

- Singly Linked Lists
	- Iterating over a List: This is the easy part of the problem... just iterate over the list 
		`````
		//Define a IntegerCell
		class IntegerCell{
			public int Value;
			public IntegerCell Next;
		}

		Iterate(Cell : Top)
			While (top != null)
				Print top.Value
				top = top.Next
			End While
		End Iterate
		`````
	- Finding Cells: Simply a matter of iterating over a list and stopping when you find the cell you want
	- Using Sentinels: The first value that the algorithm examines is in the list's second cell, and it never looks back. One way to handle this situation is to add special-purpose code that explicitly looks for the target value in the first cell and then handles that case specially. The program would probably need to handle this situation as a special case, and it could get messy. Another approach is to create a sentinel at the beginning of the list. A sentinel is a cell that is part of the linked list but that doesn't contain any meaningful data. It is used only as a placeholder so that algorithms can refer to a cell that comes before the first cell.

	- Adding Cells at the Beginning: One use for linked lists is to provide a data structure where you can store items. This is sort of like an array that you can expand whenever you need more space. The easiest way to add an item to a linked list is to place a new cell at the beginning, right after the sentinel. 
	- Adding Cells at the End: One use for linked lists is to provide a data structure where you can store items. This is sort of like an array that you can expand whenever you need more space. The easiest way to add an item to a linked list is to place a new cell at the beginning, right after the sentinel.
	- Inserting Cells after other Cells
	- Deleting Cells
- Doubly Linked Lists
- Sorted Linked Lists
- Linked-List Algorithms
	- Copying Lists
	- Sorting with Insertion Sort
- Linked List Selectionsort
- Multithreaded Linked Lists
- Linked Lists with Loops
	- Marking Cells
	- Using Hash Tables
	- List Retracing
	- List Reversal

###4. Arrays
- One-dimensional Arrays
- Nonzero Lower Bounds
- Triangular Arrays
- Sparse Arrays
- Matrices 

###5. Stacks and Queues
- Stacks
- Queues

###6. Sorting
- O(N^2) Algorithms
- O(N Log N) Algorithms
- Sub O(N Log N) Algorithms

###7. Searching
- Linear Search
- Binary Search
- Interpolation Search

###8. Hash Tables
- Fundamentals
- Chaining
- Open Addressing

###9. Recursion
- Basic Algorithms
- Graphical Algorithms
- Backtracking Algorithms
- Selections and Permutations
- Recursion Removal

###10. Trees
- Tree Terminology
- Binary Tree Properties
- Tree Representations
- Tree Traversal
- Sorted Trees
- Threaded Trees
- Specialized Tree Algorithms 

###11. Balanced Trees
- AVL Trees
- 2-3 Trees
- B-Trees
- Balanced Tree Variations

###12. Decision Trees
- Searching Game Trees
- Searching General Decision Trees 

###13. Basic Network Algorithms
- Network Terminology
- Network Representations
- Traversals
- Finding Paths 

###14. More Network Algorithms
- Topological Sorting
- Cycle Detection
- Map Coloring
- Maximal Flow 

###15. String Algorithms
- Matching Parentheses
- Pattern Matching
- String Searching
- Calculating Edit Distance

###16. Cryptography
- Transposition Ciphers
- Substitution Ciphers
- Block Ciphers
- Public-Key Encryption and RSA

###17. Complexity Theory
- Notation
- Complexity Classes
- Reductions
- NP-Hardness
- Detection, Reporting, and Optimization Problems
- NP-Complete Problems

###18. Distributed Algorithms
- Types of Parallelism
- Distributed Algorithms

###19. Interview Puzzles
- Asking Interview Puzzle Questions
- Answering Interview Puzzle Questions
