# Binary Search Tree(BST)

![](imgs/bst.png)

Binary search tree is a data structure that quickly allows us to maintain a sorted list of numbers.

* It is called a binary tree because each tree node has a maximum of two children.
* It is called a search tree because it can be used to search for the presence of a number in `O(log(n))` time.

The properties that separate a binary search tree from a regular [binary tree](https://www.programiz.com/data-structures/trees) is

* All nodes of left subtree are less than the root node
* All nodes of right subtree are more than the root node
* Both subtrees of each node are also BSTs i.e. they have the above two properties

## Operations

* Search
* Insert
* Delete

## Complexities

n = number of nodes

### Time Complexities


| **Operation** | **Best Case Complexity** | **Average Case Complexity** | **Worst Case Complexity** |
| - | - | - | - |
| Search | O(log n) | O(log n) | O(n) |
| Insertion | O(log n) | O(log n) | O(n) |
| Deletion | O(log n) | O(log n) | O(n) |

### Space Complexities

The space complexity for all the operations is` O(n)`.

## Applications

* In multilevel indexing in the database
* For dynamic sorting
* For managing virtual memory areas in Unix kernel
