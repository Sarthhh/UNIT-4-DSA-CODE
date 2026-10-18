##  Employee ID Directory Using Threaded Binary Search Tree

The Employee ID Directory Using Threaded Binary Search Tree (TBT) is a C++ project designed to manage employee identification numbers efficiently. The project uses a Threaded Binary Search Tree data structure to store employee IDs in sorted order and perform operations such as insertion, searching, and traversal.

In a traditional binary search tree, some child pointers remain NULL when a node has no left or right child. In a threaded binary search tree, these pointers are used to store links to the node’s inorder predecessor or successor. This approach allows efficient inorder traversal without requiring recursion or an auxiliary stack.

The program provides a menu-driven interface that allows users to insert employee IDs, display IDs in ascending order, find the inorder predecessor and successor of a particular employee ID, and display the preorder traversal of the tree. It also prevents duplicate employee IDs from being inserted.

### Objectives

- To implement a threaded binary search tree using C++.
- To maintain employee IDs in sorted order.
- To enable efficient inorder traversal using threaded pointers.
- To find the predecessor and successor of a given employee ID.
- To demonstrate insertion, searching, and preorder traversal in a tree data structure.
- To prevent duplicate entries and provide a simple, interactive menu.

### Key Features

1. Insert Employee ID: Adds a new employee ID while maintaining the binary search tree structure and threading.
2. Inorder Traversal: Displays all employee IDs in ascending order by following successor threads.
3. Find Predecessor and Successor: Identifies the employee ID immediately before and after a specified ID in sorted order.
4. Preorder Traversal: Displays the tree nodes in root-left-right order.
5. Duplicate ID Detection: Prevents the insertion of an employee ID that already exists.
6. Menu-Driven Interface: Allows users to perform multiple operations until they choose to exit.

### Technologies Used

- Programming Language: C++
- Data Structure: Threaded Binary Search Tree
- Concepts: Pointers, structures, dynamic memory allocation, searching, insertion, and tree traversal.

### Applications

This project demonstrates how threaded binary search trees can be used in employee directories, sorted record management systems, and other applications that require ordered data retrieval and traversal.

### Conclusion

The Employee ID Directory project provides a practical demonstration of threaded binary search trees in C++. It helps users understand how threaded pointers improve inorder traversal and how predecessor and successor operations can be performed efficiently. The project strengthens understanding of non-linear data structures, pointer manipulation, and dynamic memory management.
