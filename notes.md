# Linked Lists

## Objectives

* Describe linked lists
- list of elements that can be easily inserted and removed without reallocation or reorganization of the entire structure
  - A linear collection of data elements, called nodes, referencing the next node by means of a pointer
    - MUST be read sequentially
    - Efficient for using Linked Lists for stacks and queues because they are always accessing the front or end of a dataset, nothing in-between
- Computation:
  - O(1) for insertion and deletion (least computational power required)
  - O(n) for Random Access (n is the number of nodes)
  - Arrays are inversely related -- O(n) for insertion/deletion, O(1) for Random access.

- Members:
  - Insert
    - Append a node to the list
  - Remove
    - Remove a node from the list
  - Indexing
    - retrieve a node by index
  - Head
    - Start of the list
  - Tail
    - End of the list

- Nodes: data inside a linked list (similar to elements in an array)
  - will store data
  - AND a reference to other nodes through pointers

* Diagram linked lists
[Linked List diagram](https://www.geeksforgeeks.org/data-structures/linked-list/)




* STRETCH: review code implementation of linked lists

## Resources

* [Slides - Linked Lists](https://docs.google.com/presentation/d/1VmmQp-07Ed7i5iK8ZvDNB_4coZyEw1Pr0XrwFCtj128/edit#slide=id.g11adedd999_0_1)
* [Learn - Linked Lists](https://learn-2.galvanize.com/cohorts/757/blocks/61/content_files/Linked%20Lists/01-Linked%20List%20Intro.md)
* [Learn - Singly Linked Lists](https://learn-2.galvanize.com/cohorts/757/blocks/61/content_files/Linked%20Lists/02-SinglyLinkedList.md)
* [Learn - Doubly Linked Lists](https://learn-2.galvanize.com/cohorts/757/blocks/61/content_files/Linked%20Lists/03-DoublyLinkedList.md)
* [Video - Arrays vs Linked Lists](https://www.youtube.com/watch?v=lC-yYCOnN8Q)
* [Arrays vs Linked Lists Cheatesheet](https://github.com/gSchool/describe-arrays-linked-lists/blob/master/drills/version-1/rubric.md)
