# Binary Tree

![](image.png)

* A binary tree is a tree data structure in which each parent node can have at most two children.
* Each node of a binary tree consists of three items:

  * data item
  * address of left child
  * address of right child

## Types of binary tree:

* Full Binary Tree
  * A full Binary tree is a special type of binary tree in which every parent node/internal node has either two or no children.
* Perfect Binary Tree
  * A perfect binary tree is a type of binary tree in which every internal node has exactly two child nodes and all the leaf nodes are at the same level.
* Complete Binary Tree
  * A complete binary tree is just like a full binary tree, but with two major differences
    * Every level must be completely filled
    * All the leaf elements must lean towards the left.
    * The last leaf element might not have a right sibling i.e. a complete binary tree doesn't have to be a full binary tree.
* Degenerate or Pathological Tree
  * A degenerate or pathological tree is the tree having a single child either left or right.
* Skewed Binary Tree
  * A skewed binary tree is a pathological/degenerate tree in which the tree is either dominated by the left nodes or the right nodes.
  * Types
    * left-skewed binary tree
    * right-skewed binary tree
* Balanced Binary Tree
  * It is a type of binary tree in which the difference between the height of the left and the right subtree for each node is either 0 or 1.

## Applications

* For easy and quick access to data
* In router algorithms
* To implement [heap data structure](https://www.programiz.com/dsa/heap-data-structure)
* Syntax tree
