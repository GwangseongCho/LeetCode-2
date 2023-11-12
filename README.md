# LeetCode-2

Comment every line of code for understanding
## Data Structure
Abstract Data Type
ADT is an abstraction of data structure which provides only the interface to which a data structure must adhere to.
The interface does not give any specific details about how something should be implemented or in which programming language.
* List  - Dynamic Array, Linked List
* Queue - Linked list based Queue, Array based Queue, Stack based Queue
* Map - Tree Map, Hash Map, Hash Table

Computational Complexity Analysis
Time and Space 
Big O notation give an upper bound of the complexity in the worst case.


## Array
### Static and Dynamic Arrays
What is an Staic Array?
A static array us a fixed length container containing n elements indexiable from the range [0, n-1]
idexiable = array can be referenced with a number.

### Static Arrary vs Dynamic Array
Access	O(1)	O(1)
Serach	O(n)	O(n)
Insertion	N/A	O(n)
Appending	N/A	O(1)
Deletion	N/A	O(n)
### Dynamic Array
The dynamic array can grow and shrink in size.
How can we implement a dynamic array?
Q: One way is to use static array.
1. Create static array with an initial capacity
2. Add element to the underlying static array.
3. If the array exceed the capacity, then create a new static array with twice the capacity and copy the original elements into it.

## HashMap

## Stack

## Queue

## Two Pointer
