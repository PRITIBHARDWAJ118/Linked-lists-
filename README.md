# Linked-lists
# Aim:
To study and implement Linked list 
# Theory:
A linked list is a linear data structure where each element, called a "node," contains a data part and a reference (or pointer) to the next node in the sequence. Unlike arrays, linked lists are not stored in contiguous memory locations.

## Types of Linked Lists:

1. Singly Linked List: Each node contains data and a pointer to the next node.
* The first node is called the head of the list.
* The last node’s next pointer is NULL, indicating the end of the list.
* The traversal of the list is unidirectional; you can only traverse it from the head to the end.
* Operations like insertion, deletion, and traversal are straightforward but limited in terms of backward traversal.
2. Doubly Linked List: Each node contains data, a pointer to the next node, and a pointer to the previous node.
* The first node’s previous pointer is NULL, and the last node’s next pointer is NULL.
* You can traverse the list both forward and backward.
* The list is more complex due to the extra pointer, but it is also more flexible.
3. Circular Linked List: The last node in the list points to the first node, making the list circular.
* There is no NULL pointer to indicate the end of the list.
* The list can be traversed endlessly unless specifically stopped.
* Circular nature allows for a loop-like structure.
