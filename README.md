# Binary Tree Project

This project aims to enhance your understanding of binary trees and related concepts. The learning objectives include grasping the fundamentals of binary trees, distinguishing between a binary tree and a Binary Search Tree (BST), exploring time complexity gains compared to linked lists, and understanding key terms such as depth, height, and size of a binary tree.

## Table of Contents

- [General Overview](#general-overview)
- [Binary Tree vs Binary Search Tree](#binary-tree-vs-binary-search-tree)
- [Time Complexity Comparison](#time-complexity-comparison)
- [Key Terminology](#key-terminology)
- [Traversal Methods](#traversal-methods)
- [Types of Binary Trees](#types-of-binary-trees)
- [Coding Requirements](#coding-requirements)

## General Overview

### What is a Binary Tree?

A binary tree is a hierarchical data structure composed of nodes, where each node has at most two children, referred to as the left child and the right child.

## Binary Tree vs Binary Search Tree

### Binary Tree vs Binary Search Tree

A binary search tree (BST) is a specific type of binary tree where the left child of a node contains values less than or equal to the node, and the right child contains values greater than the node.

## Time Complexity Comparison

### Time Complexity Gain Compared to Linked Lists

Binary trees can offer improved time complexity for certain operations compared to linked lists. For example, searching, insertion, and deletion can be more efficient in a binary tree, particularly a balanced one.

## Key Terminology

### Depth, Height, and Size of a Binary Tree

- **Depth:** The depth of a node is the length of the path from the root to that node.
- **Height:** The height of a node is the length of the longest path to a leaf from that node.
- **Size:** The size of a binary tree is the total number of nodes in the tree.

## Traversal Methods

### Traversal Methods

There are different ways to traverse a binary tree:

- **In-order traversal:** Visit left subtree, visit root, visit right subtree.
- **Pre-order traversal:** Visit root, visit left subtree, visit right subtree.
- **Post-order traversal:** Visit left subtree, visit right subtree, visit root.

## Types of Binary Trees

### Complete, Full, Perfect, Balanced Binary Trees

- **Complete Binary Tree:** A binary tree in which every level, except possibly the last, is completely filled, and all nodes are as left as possible.
- **Full Binary Tree:** A binary tree in which every node has either 0 or 2 children.
- **Perfect Binary Tree:** A binary tree in which all the leaf nodes are at the same level, and every internal node has exactly two children.
- **Balanced Binary Tree:** A binary tree is balanced if the height of the left and right subtrees of any node differ by no more than one.

## Coding Requirements

- Use allowed editors: vi, vim, emacs.
- Compile on Ubuntu 20.04 LTS using gcc with specified options.
- Follow the Betty style for code formatting.
- No more than 5 functions per file.
- Do not use global variables.
- Include prototypes in the header file named `binary_trees.h`.
- Push the header file and ensure it's include guarded.
- Include a `README.md` file at the root of the project.

Remember, understanding and implementing these concepts in your code will solidify your understanding of binary trees and related topics. Good luck with your project!
