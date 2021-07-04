# Bucket Sort

![](https://cdn.programiz.com/cdn/farfuture/gNSELV0jV05rlFjkjScrcZWCFeRsJqJUczwEOcne9D0/mtime:1582112622/sites/tutorial2program/files/Bucket_2.png)


## Working of Bucket Sort

1. Suppose, the input array is:![Bucket Sort Steps](https://cdn.programiz.com/cdn/farfuture/nZnEPMDyED_o3k9I9B_kA62pnHztKRSQy2CjCqLRI0I/mtime:1582112622/sites/tutorial2program/files/Bucket-sort-0.1_0.png "Original Array")Input array
   Create an array of size 10. Each slot of this array is used as a bucket for storing elements.![Bucket Sort Steps](https://cdn.programiz.com/cdn/farfuture/Vfhp1cQfAtSDdhNoGxyahhZ1usg1tFN-048etgx7w7k/mtime:1582112622/sites/tutorial2program/files/Bucket-sort-0_0.png "Bubble Sort step 0")
2. Insert elements into the buckets from the array. The elements are inserted according to the range of the bucket.

   In our example code, we have buckets each of ranges from 0 to 1, 1 to 2, 2 to 3,...... (n-1) to n.
   Suppose, an input element is `.23` is taken. It is multiplied by `size = 10` (ie. `.23*10=2.3`). Then, it is converted into an integer (ie. `2.3≈2`). Finally, .23 is inserted into **bucket-2**.![Bucket Sort Steps](https://cdn.programiz.com/cdn/farfuture/hREOdaen0Rf3tOH3peobau0_r1NK0tB8B3OsChICkc0/mtime:1582112622/sites/tutorial2program/files/Bucket-sort-0.2_0.png "Bucketing")Insert elements into the buckets from the array
   Similarly, .25 is also inserted into the same bucket. Everytime, the floor value of the floating point number is taken.

   **If we take integer numbers as input, we have to divide it by the interval (10 here) to get the floor value.**

   Similarly, other elements are inserted into their respective buckets.![Bucket Sort Steps](https://cdn.programiz.com/cdn/farfuture/zNeS_ImQpS0e-lHiTIZC5tLlOuX4M58TwCaZV8tveOE/mtime:1582112622/sites/tutorial2program/files/Bucket-sort-0.3_0.png "Bucketing Completed")
3. The elements of each bucket are sorted using any of the stable sorting algorithms. Here, we have used quicksort (inbuilt function).![Bucket Sort Steps](https://cdn.programiz.com/cdn/farfuture/mOL3yaTcJAp3WbD0kTJq7rWgnLl6nMrR762voPIsyN8/mtime:1582112622/sites/tutorial2program/files/Bucket-sort-0.4_0.png "Elements sorted in each bucket")
4. The elements from each bucket are gathered.

   It is done by iterating through the bucket and inserting an individual element into the original array in each cycle. The element from the bucket is erased once it is copied into the original array.![Bucket Sort Steps](https://cdn.programiz.com/cdn/farfuture/VobtThxrLKyQDQa8o5gUKmCAHBAJzBIjZ3wEuEyL8Fc/mtime:1582112622/sites/tutorial2program/files/Bucket-sort-0.5_0.png "Gathering from buckets into original array")


## Complexity


| **Time Complexity** |   |
| - | - |
| Best | O(n+k) |
| Worst | O(n^2^) |
| Average | O(n) |
| **Space Complexity** | O(n+k) |
| **Stability** | Yes |


## Applications

Bucket sort is used when:

* input is uniformly distributed over a range.
* there are floating point values

## Similar Sorting Algorithms

* [Bubble Sort](https://www.programiz.com/dsa/bubble-sort)
* [Quicksort](https://www.programiz.com/dsa/quick-sort)
* [Insertion Sort](https://www.programiz.com/dsa/insertion-sort)
* [Merge Sort](https://www.programiz.com/dsa/merge-sort)
* [Selection Sort](https://www.programiz.com/dsa/selection-sort)
