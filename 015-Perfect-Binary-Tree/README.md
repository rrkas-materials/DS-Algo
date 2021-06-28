# Perfect Binary Tree

![](image.png)

* A perfect binary tree is a type of binary tree in which every internal node has exactly two child nodes and all the leaf nodes are at the same level.
* All the internal nodes have a degree of 2.
* Recursively, a perfect binary tree can be defined as:
  * If a single node has no children, it is a perfect binary tree of height `h = 0`,
  * If a node has `h > 0`, it is a perfect binary tree if both of its subtrees are of height `h - 1` and are non-overlapping.

## Properties

* A perfect binary tree of height h has `2<sup>h + 1</sup><span> </span>– 1` node.
* A perfect binary tree with n nodes has height `log(n + 1) – 1 = Θ(ln(n))`.
* A perfect binary tree of height h has `2<sup>h</sup>` leaf nodes.
* The average depth of a node in a perfect binary tree is `Θ(ln(n))`.
