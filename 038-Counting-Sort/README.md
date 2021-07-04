# Counting Sort

Counting sort is [a sorting algorithm](https://www.programiz.com/dsa/sorting-algorithm) that sorts the elements of an array by counting the number of occurrences of each unique element in the array. The count is stored in an auxiliary array and the sorting is done by mapping the count as an index of the auxiliary array.


## Working of Counting Sort

1. Find out the maximum element (let it be `max`) from the given array.
2. Initialize an array of length `max+1` with all elements 0. This array is used for storing the count of the elements in the array.
3. Store the count of each element at their respective index in `count` array

   For example: if the count of element 3 is 2 then, 2 is stored in the 3rd position of count array. If element "5" is not present in the array, then 0 is stored in 5th position.
4. Store cumulative sum of the elements of the count array. It helps in placing the elements into the correct index of the sorted array.
5. Find the index of each element of the original array in the count array. This gives the cumulative count. Place the element at the index calculated as shown in figure below.
6. After placing each element at its correct position, decrease its count by one.


## Complexity


| **Time Complexity** |   |
| - | - |
| Best | O(n+k) |
| Worst | O(n+k) |
| Average | O(n+k) |
| **Space Complexity** | O(max) |
| **Stability** | Yes |


## Applications

Counting sort is used when:

* there are smaller integers with multiple counts.
* linear complexity is the need.

## Similar Sorting Algorithms

1. [Quicksort](https://www.programiz.com/dsa/quick-sort)
2. [Merge Sort](https://www.programiz.com/dsa/merge-sort)
3. [Bucket Sort](https://www.programiz.com/dsa/bucket-sort)
4. [Radix Sort](https://www.programiz.com/dsa/radix-sort)
