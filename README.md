# 📘 Linked List in C++

This repository contains simple C++ implementations of Linked List basics to help beginners understand how nodes are created, inserted, and displayed.


---

# 🚀 Introduction

A Linked List is a linear data structure where elements (called nodes) are connected using pointers.
Each node contains:

Data → the value stored in the node.

Pointer (next) → address of the next node in the list.


Unlike arrays, linked lists are dynamic and allow efficient insertions and deletions.


---

# 📂 Files in this Repository

1. Code1.cpp → Demonstrates creation of a single node in a linked list.


2. Code2.cpp → Demonstrates insertion of nodes at the head of the linked list and displays the list.



# 🔎 Algorithm (Code 1)

1. Define a class Link with:

An integer data

A pointer next to the next node



2. Create a constructor to initialize:

data with the given value

next as NULL



3. In main():

Create a new node with value 6.

Print the node’s data and pointer (next).




✅ This demonstrates the basic building block of a linked list.
# 🔎 Algorithm (Code 2)

Function: insert_head(head, data)

1. Create a new node with the given data.


2. Point new_node->next to the current head.


3. Update head to point to new_node.



Function: disp(head)

1. Initialize a temporary pointer temp = head.


2. Traverse the list:

Print temp->data followed by ->.

Move to the next node (temp = temp->next).



3. Stop when temp == NULL and print "NULL".



Main Flow

1. Start with an empty list (head = NULL).


2. Insert nodes 30, 32, and 35 at the head.


3. After each insertion, display the updated list.
# 🏁 Conclusion

This repository introduces the fundamental concepts of linked lists in C++.

Code 1 shows how a single node is created, which is the foundation of all linked list operations.

Code 2 demonstrates how nodes can be inserted at the head and displayed, giving a first look at dynamic memory handling in C++.


By understanding these basics, you’ll be ready to implement more complex operations like insertion at any position, deletion, searching, and reversing a linked list.
