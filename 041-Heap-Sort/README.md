# Heap Sort

Heap Sort is a popular and efficient [sorting algorithm](https://www.programiz.com/dsa/sorting-algorithm) in computer programming. Learning how to write the heap sort algorithm requires knowledge of two types of data structures - arrays and trees.

## Heap Data Structure?

Heap is a special tree-based data structure. A binary tree is said to follow a heap data structure if

* it is [a complete binary tree](https://www.programiz.com/dsa/complete-binary-tree)
* All nodes in the tree follow the property that they are greater than their children i.e. the largest element is at the root and both its children and smaller than the root and so on. Such a heap is called a max-heap. If instead, all nodes are smaller than their children, it is called a min-heap

![](https://cdn.programiz.com/cdn/farfuture/ku9PI_QBgYEk3neZkm92PDkwkvQzbTQX_aSYg_Ns6M0/mtime:1586942755/sites/tutorial2program/files/max-heap-min-heap.png)


## Working of Heap Sort

1. Since the tree satisfies Max-Heap property, then the largest item is stored at the root node.
2. **Swap:** Remove the root element and put at the end of the array (nth position) Put the last item of the tree (heap) at the vacant place.
3. **Remove:** Reduce the size of the heap by 1.
4. **Heapify:** Heapify the root element again so that we have the highest element at root.
5. The process is repeated until all the items of the list are sorted.


## Complexity


| **Time Complexity** |   |
| - | - |
| Best | O(nlog n) |
| Worst | O(nlog n) |
| Average | O(nlog n) |
| **Space Complexity** | O(1) |
| **Stability** | No |


## Applications

Systems concerned with security and embedded systems such as Linux Kernel use Heap Sort because of the `O(n log n)` upper bound on Heapsort's running time and constant `O(1)` upper bound on its auxiliary storage.

Although Heap Sort has `O(n log n)` time complexity even for the worst case, it doesn't have more applications ( compared to other sorting algorithms like Quick Sort, Merge Sort ). However, its underlying data structure, heap, can be efficiently used if we want to extract the smallest (or largest) from the list of items without the overhead of keeping the remaining items in the sorted order. For e.g Priority Queues.

## Similar Sorting Algorithms

1. [Quicksort](https://www.programiz.com/dsa/quick-sort)
2. [Merge Sort](https://www.programiz.com/dsa/merge-sort)
