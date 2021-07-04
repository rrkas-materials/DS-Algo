# Quicksort

Quicksort is [a sorting algorithm](https://www.programiz.com/dsa/sorting-algorithm) based on the **divide and conquer approach** where

1. An array is divided into subarrays by selecting a **pivot element** (element selected from the array).

   While dividing the array, the pivot element should be positioned in such a way that elements less than pivot are kept on the left side and elements greater than pivot are on the right side of the pivot.
2. The left and right subarrays are also divided using the same approach. This process continues until each subarray contains a single element.
3. At this point, elements are already sorted. Finally, elements are combined to form a sorted array.

## Complexity


| **Time Complexity** |   |
| - | - |
| Best | O(n*log n) |
| Worst | O(n^2^) |
| Average | O(n*log n) |
| **Space Complexity** | O(log n) |
| **Stability** | No |



## Applications

Quicksort algorithm is used when

* the programming language is good for recursion
* time complexity matters
* space complexity matters

## Similar Sorting Algorithms

* [Insertion Sort](https://www.programiz.com/dsa/insertion-sort)
* [Merge Sort](https://www.programiz.com/dsa/merge-sort)
* [Selection Sort](https://www.programiz.com/dsa/selection-sort)
* [Bucket Sort](https://www.programiz.com/dsa/bucket-sort)
