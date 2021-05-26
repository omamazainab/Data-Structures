# Binary Tree Data Structure
A tree whose elements have at most 2 children is called a binary tree. Since each element in a binary tree can have only 2 children, we typically name them the left and right child.

A Binary Tree node contains following parts.

1. Data
2. Pointer to left child
3. Pointer to right child

## Introduction

- Trees are hierarchical data structures.
- The topmost node is called root of the tree. 
- The elements that are directly under an element are called its children. 
- The element directly above other element is called its parent. 
- Finally, elements with no children are called leaves. 
- All keys in left subtree of a key must be smaller and all keys in right subtree must be greater. So a Binary Search Tree by definition has distinct keys and duplicates in binary search tree are not allowed.

### Why trees?
 - One reason to use trees might be because you want to store information that naturally forms a hierarchy. For example, the file system on a computer.

 - Trees (with some ordering e.g., BST) provide moderate access/search (quicker than Linked List and slower than arrays)

 - Trees provide moderate insertion/deletion (quicker than Arrays and slower than Unordered Linked Lists)

 - Like Linked Lists and unlike Arrays, Trees don’t have an upper limit on number of nodes as nodes are linked using pointers.