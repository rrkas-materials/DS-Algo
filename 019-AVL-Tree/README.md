# AVL Tree

![](image.webp)

AVL tree is a self-balancing binary search tree in which each node maintains extra information called a balance factor whose value is either -1, 0 or +1.

AVL tree got its name after its inventor Georgy Adelson-Velsky and Landis.

* Balance Factor = (Height of Left Subtree - Height of Right Subtree) or (Height of Right Subtree - Height of Left Subtree)
* The value of balance factor should always be -1, 0 or +1

## Operations

* Rotating the subtrees
  * In left-rotation, the arrangement of the nodes on the right is transformed into the arrangements on the left node.
  * In right-rotation, the arrangement of the nodes on the left is transformed into the arrangements on the right node.
  * In left-right rotation, the arrangements are first shifted to the left and then to the right.
* insertion
* delete

## Complexity


| **Insertion** | **Deletion** | **Search** |
| - | - | - |
| O(log n) | O(log n) | O(log n) |

## Applications

* For indexing large records in databases
* For searching in large databases
