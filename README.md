# LINKED-LIST-IMPLEMENTATION

*COMPANY NAME*: CODTECH IT SOLUTION

*NAME*: MD MAHMUD HUSSAIN

*INTERN ID*: CTISAK20 

*DOMAIN*: C PRAOGAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

Introduction

Task 2 of the CODTECH Internship is focused on the implementation of a Singly Linked List using the C programming language. Data structures are the backbone of efficient programming, and among them, the linked list is one of the most fundamental and widely used dynamic data structures. This task aims to provide practical exposure to how data can be stored, managed, and manipulated dynamically in memory without relying on fixed-size structures like arrays.

Unlike arrays, which require contiguous memory allocation and have a fixed size, linked lists offer flexibility by allowing dynamic memory allocation. This task helps in understanding how memory management, pointers, and structures work together to form an efficient data structure.

Objective of the Task

The primary objectives of Task 2 are:

To understand the concept and structure of a singly linked list.

To learn dynamic memory allocation using malloc() and free().

To implement basic linked list operations:

Insertion

Deletion

Traversal (Display)

To design a menu-driven program for better user interaction.

To strengthen understanding of pointers and structures in C.

To develop logical thinking for data manipulation.

Concept of Singly Linked List

A singly linked list is a linear data structure where each element, called a node, consists of two parts:

Data – Stores the actual value.

Next pointer – Stores the address of the next node in the list.

The first node of the list is called the head, and the last node points to NULL, indicating the end of the list.

Structure of a Node
struct Node {
    int data;
    struct Node* next;
};


This structure allows each node to link to the next node, forming a chain-like structure in memory.

Why Linked List Instead of Array?

Linked lists overcome several limitations of arrays:

Dynamic size (no fixed memory requirement)

Efficient insertion and deletion

Better memory utilization

No shifting of elements required

These advantages make linked lists suitable for applications where data size changes frequently.

Description of the Implemented Program

The implemented program in Task 2 is a menu-driven singly linked list program written in C. The program allows the user to perform operations repeatedly until they choose to exit.

The main operations implemented are:

1. Insertion Operation

Insertion is the process of adding a new node to the linked list. In this program, insertion is performed at the end of the list.

Steps involved:

Allocate memory for a new node using malloc().

Accept user input for the node’s data.

Set the next pointer of the new node to NULL.

If the list is empty, assign the new node as the head.

Otherwise, traverse the list to the last node and link it to the new node.

This operation demonstrates dynamic memory allocation and traversal logic.

2. Deletion Operation

Deletion removes a node from the linked list. In this task, deletion is performed from the beginning of the list.

Steps involved:

Check if the list is empty.

If empty, display an appropriate message.

Otherwise, store the head node in a temporary pointer.

Move the head to the next node.

Free the memory of the deleted node using free().

This operation highlights proper memory deallocation to avoid memory leaks.

3. Traversal (Display) Operation

Traversal involves visiting each node of the linked list and displaying its data.

Steps involved:

Check if the list is empty.

Start from the head node.

Move through the list until NULL is reached.

Print the data of each node in sequence.

The output format clearly shows the structure of the linked list, making it easy to understand.

Menu-Driven Approach

A menu-driven interface is implemented to make the program user-friendly and interactive. The menu repeatedly prompts the user to choose an operation:

Insert

Delete

Display

Exit

This approach allows the user to test multiple operations in a single execution and improves usability.

Error Handling

The program includes basic error handling to ensure safe execution:

Checks for empty list before deletion or traversal

Validates memory allocation

Displays clear messages for invalid choices

These checks prevent runtime errors and improve program reliability.

Technologies and Tools Used

Programming Language: C

Compiler: GCC

IDE/Editor: Visual Studio Code

Platform: Cross-platform (Windows, macOS, Linux)

Program Output

The output of the program is displayed in the terminal. It includes:

A clear menu interface

Confirmation messages for insertion and deletion

Display of linked list elements in proper sequence

Example output:

Linked List: 10 -> 20 -> 30 -> NULL


This format helps visualize the linked list structure clearly.

Applications of Linked Lists

Linked lists are widely used in real-world applications such as:

Dynamic memory management

Implementation of stacks and queues

Music and video playlists

Undo/redo operations

Graph and tree data structures

Understanding linked lists is essential for mastering advanced data structures.

Learning Outcomes

After completing Task 2, the following concepts were learned:

Structure and working of singly linked lists.

Dynamic memory allocation and deallocation.

Effective use of pointers.

Implementation of basic data structure operations.

Writing modular and readable C programs.

Designing menu-driven applications.

Conclusion

Task 2 provides a strong foundation in data structures by implementing a singly linked list in C. Through insertion, deletion, and traversal operations, this task demonstrates how dynamic memory and pointers can be effectively used to manage data. The menu-driven approach makes the program interactive and easy to test.

Completing this task significantly improves understanding of linked lists and prepares the learner for more advanced data structures such as doubly linked lists, stacks, queues, trees, and graphs. This task is an essential step toward becoming proficient in system-level and application-level programming.

#OUTPUT

<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/e7a270fe-e76f-4b91-8921-8a1cd2f85f44" />

