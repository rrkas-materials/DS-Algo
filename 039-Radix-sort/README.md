# Radix Sort

Radix sort is [a sorting algorithm](https://www.programiz.com/dsa/sorting-algorithm) that sorts the elements by first grouping the individual digits of the same **place value**. Then, sort the elements according to their increasing/decreasing order.

Suppose, we have an array of 8 elements. First, we will sort elements based on the value of the unit place. Then, we will sort elements based on the value of the tenth place. This process goes on until the last significant place.


## Working of Radix Sort

1. Find the largest element in the array, i.e. max. Let `X` be the number of digits in `max`. `X` is calculated because we have to go through all the significant places of all elements.

   In this array `[121, 432, 564, 23, 1, 45, 788]`, we have the largest number 788. It has 3 digits. Therefore, the loop should go up to hundreds place (3 times).
2. Now, go through each significant place one by one.

   Use any stable sorting technique to sort the digits at each significant place. We have used counting sort for this.

   Sort the elements based on the unit place digits (`X=0`).![Radix Sort working with Counting Sort as intermediate step](https://cdn.programiz.com/cdn/farfuture/uCNpqDxCh0fa6L5HIYKbmYCbiZHlGhzXXBsxKVpItSs/mtime:1591330108/sites/tutorial2program/files/Radix-sort-one.png "Radix Sort Steps")
3. Now, sort the elements based on digits at tens place.![Radix Sort Step](https://cdn.programiz.com/cdn/farfuture/k2d_8gQeDKJ5pafc96mpZMqZvEqOOrh9eBCVmKRTBsg/mtime:1591330113/sites/tutorial2program/files/Radix-sort-ten.png "Radix Sort Step")
4. Finally, sort the elements based on the digits at hundreds place.![Selection Sort Step](https://cdn.programiz.com/cdn/farfuture/CvIF-W6hxb0-kwt-hn9Gb3IWlpTVxR3PK7X4TQimROc/mtime:1591330096/sites/tutorial2program/files/Radix-sort-hundred.png "Selection Sort Step")


## Complexity


| **Time Complexity** |   |
| - | - |
| Best | O(n+k) |
| Worst | O(n+k) |
| Average | O(n+k) |
| **Space Complexity** | O(max) |
| **Stability** | Yes |



## Applications

Radix sort is implemented in

* DC3 algorithm (Kärkkäinen-Sanders-Burkhardt) while making a suffix array.
* places where there are numbers in large ranges.

## Similar Sorting Algorithms

1. [Quicksort](https://www.programiz.com/dsa/quick-sort)
2. [Merge Sort](https://www.programiz.com/dsa/merge-sort)
3. [Bucket Sort](https://www.programiz.com/dsa/bucket-sort)
4. [Counting Sort](https://www.programiz.com/dsa/counting-sort)
