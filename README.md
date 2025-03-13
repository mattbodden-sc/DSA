# DSA
Data Structures &amp; Algorithms examples

## Exercises

### Fibonacci
The fibonacci sequence is a mathematical sequence of numbers that goes like
this until infinity: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ... The next number can
be found by adding up the two numbers before it, and the first two numbers are
always 0 and 1. Write a function that accepts a number, n, and returns the nth
number of the fibonacci sequence. For example, if the input was 10, the function
should return 55 since that's the 10th number in the sequence. The first number
0 is considered the 0th number in the sequence. so 1 is the 1st.

### Array subset
How could we write a function that compares two arrays and lets us know if one is a subset of the other?

### First Duplicate
Write a function that accepts an array of strings and returns the first
duplicate value it finds. For example, if the array is
["a", "b", "c", "d", "c", "e", "f"], the function should return "c", since
it's duplicated within the array. You can assume there is only one duplicate
within the array. Make sure the function has a complexity of O(N).

### First Non Duplicate
Write a function that returns the first non-duplicated character in a string.
For example, the string "minimum" has two characters that only appear once:
the "n" and the "u". The function should return "n" since it appears first.
The function should have an efficiency of O(N).

### Intersection
Write a function that returns the intersection of two arrays. The intersection
is a third array that contains all values contained within the first two
arrays. For example, the intersection of [1, 2, 3, 4, 5] and [0, 2, 4, 6, 8]
is [2, 4].
Your function should have a complexity of O(N).

### Missing Letter
Write a function that accepts a string that contains all the letters of the
alphabet except one and returns the missing letter. For example, the string
"the quick brown box jumps over a lazy dog" contains all the letters of the
alphabet except the letter "f". Your function should have a complexity of
O(N).

### Implement a Doubly Linked List
One variant form of a linked-list is the doubly linked-list.
A doubly-linked-list is like a lined-list except that each node has two
links - one that points to the next node, and another that points to the
previous node. In addition, the doubly linked list always keeps track of
both the first and last nodes in the list, instead of just the first node.
This makes it easy to add and remove nodes from either end of the list.
Which makes them a good choice for implementing a Queue.

### Implement a Linked List
Linked List - a node based data structure
each node has a value and a pointer to the next node, the pointer creates 
the link between the nodes. The last node points to None.
The first node is known as the head and the last node is known as the tail.

### Count Characters in Array of Strings
Use recursion to write a function that accepts an array of strings and
returns the total number of characters across all the strings. For example,
if the input array is ['ab', 'c', 'def', 'ghij'], the output should be 10
since there are 10 characters in total.

### Needle in a Haystack
Write a function find_needle() that takes a list full of junk and tells you if the needle
you are looking for is present.

### Only Even
Use recursion to write a function that accepts an array of numbers and
returns a new array containing just the even numbers.

### Palindromes
Write a simple function to check if a string is a palindrome

### Triangular Numbers
There is a numerical sequence known as 'Triangular Numbers'. The pattern
begins as 1, 3, 6, 10, 15, 21, and continues onward with the Nth number in the
pattern, which is N plus the previous number. For example, the 7th number in
the sequence is 28, since it's 7 (which is N) plus 21 (the previous number).
Write a function that accepts a number N and returns the correct number from
the series. That is, if the function was passed the number 7, it would return
28.

### Implement a Queue
A Queue is a data structure that stores items in a First In First Out (FIFO) manner.
Queues are similar to stacks, but they have a different set of rules.
They are arrays with the following three rules:
- Data can be inserted only at the end of a queue
- Data can be removed only from the front of a queue
- Only the first element of a queue can be read

### Anagram Generator
anagram generator using recursion for a given string
this has a time complexity of O(n!) and a space complexity of O(n!)
where n is the number of characters in the string
n! is factorial n, which is n * (n-1) * (n-2) * ... * 1
this is the slowest form of algorithm.

### Count the number of 'x's in a string
Write a recursive function to count the number of x's in a string

### Calculate the factorial
Write a function to calculate the factorial of a given number.

### Number of paths
Write a function to calculate the total number of paths to climb a staircase of n steps, taking steps of
size 1, 2, or 3

### Reverse a string
Write a function that will reverse a string

### Sum of array
Write a function that will calculate the sum of array.

### Binary Search
Implement binary search algorithm

### Implement a sorting algorithm
Same as current - provides example solutions

### Implement a Stack / Create a linter / Reverse a string
All can be done using a Stack Data Structure.

Implement a Stack Data Structure.

Write a function that uses a Stack to reverse a string.

Write a function that uses a Stack to check if a given string contains matching pairs of brackets, e.g. ({[]}) should return True, ([}]) should return False.
