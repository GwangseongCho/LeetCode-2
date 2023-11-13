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
## List 
Singly and Doubly Linked List
What is a linked list?
A linked list is a sequential list of nodes that hold data which point to other nodes also containing data.
- Head : The first node in a linkied list.
- Tail: The last node in a linked list.
- Pointer: Reference to another node
- Node: An object containing data and pointers.

Singly vs Doubly Linked Lists
Slngly linked list only hold a reference to the next node. In the implementation you always maintain a reference to the head to the linked lilst and a reference to the tail node for quick additions / removals.

Doubly linked list each node hold a reference to the next and previous node. In the implementaion you always maintain a reference to the head and the tails of the doubly linked list to do quick additions / remonals from both end of your list.


Pros vs Cons
Singly Linked	Uses less memory Simpler implementaion	Cannot easily access previous elements
Doubly Linked	Can be traversed backwards	Takes 2x memory.





Complexity
Singly linked vs Doubly
Search	O(n)	O(n)
Insert at head and tail	O(1)	O(1)
Remove at head	O(1)	O(1)
Remove at tail	O(n)	O(n1)
Remove in middle	O(n)	O(n)
## HashMap

## Stack

## Queue

## Two Pointer
