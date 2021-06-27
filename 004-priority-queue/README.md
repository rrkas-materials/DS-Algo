# Priority Queue

![](image.png)

* A priority queue is a **special type of queue** in which each element is associated with a **priority value**.
* In a queue, the **first-in-first-out rule** is implemented whereas, in a priority queue, the values are removed **on the basis of priority**. The element with the highest priority is removed first.
* implementation of priority queue


| Operations | peek | insert | delete |
| - | - | - | - |
| Linked List | `O(1)` | `O(n)` | `O(1)` |
| Binary Heap | `O(1)` | `O(log n)` | `O(log n)` |
| Binary Search Tree | `O(1)` | `O(log n)` | `O(log n)` |

* operations

  * inserting
  * deleting
* applications

  * Dijkstra's algorithm
  * for implementing stack
  * for load balancing and interrupt handling in an operating system
  * for data compression in Huffman code
