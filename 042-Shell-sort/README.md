# Shell Sort


Shell sort is a generalized version of the [insertion sort algorithm](https://www.programiz.com/dsa/insertion-sort "Insertion Sort"). It first sorts elements that are far apart from each other and successively reduces the interval between the elements to be sorted.

The interval between the elements is reduced based on the sequence used. Some of the optimal sequences that can be used in the shell sort algorithm are:

* **Shell's original sequence**: `N/2 , N/4 , …, 1`
* **Knuth's increments**: `1, 4, 13, …, (3<sup>k</sup>` `– 1) / 2`
* **Sedgewick's increments**: `1, 8, 23, 77, 281, 1073, 4193, 16577...4j+1+ 3·2j+ 1`
* **Hibbard's increments**: `1, 3, 7, 15, 31, 63, 127, 255, 511…`
* **Papernov & Stasevich increment**: `1, 3, 5, 9, 17, 33, 65,...`
* **Pratt**: `1, 2, 3, 4, 6, 9, 8, 12, 18, 27, 16, 24, 36, 54, 81....`



## Working of Shell Sort

1. Suppose, we need to sort the following array.![Shell sort step](https://cdn.programiz.com/cdn/farfuture/oCTu5VnBtOj-EguONZh7omUmqK57UWdv7K140UW58u0/mtime:1582112622/sites/tutorial2program/files/shell-sort-0.0.png "Input Array")
2. We are using the shell's original sequence `(N/2, N/4, ...1`) as intervals in our algorithm.

   In the first loop, if the array size is `N = 8` then, the elements lying at the interval of `N/2 = 4` are compared and swapped if they are not in order.

   1. The 0th element is compared with the 4th element.
   2. If the 0th element is greater than the 4th one then, the 4th element is first stored in `temp` variable and the `0th` element (ie. greater element) is stored in the `4th` position and the element stored in `temp` is stored in the `0th` position.![Shell Sort step](https://cdn.programiz.com/cdn/farfuture/DTqGWkBqy4Ui0eRi_qNJE1pothruM99CpS6N1ziBhy8/mtime:1582112622/sites/tutorial2program/files/shell-sort-0.1.png "First loop of Shell Sort")Rearrange the elements at n/2 interval
      This process goes on for all the remaining elements.![Shell Sort steps](https://cdn.programiz.com/cdn/farfuture/RM9zyvnjAlLBN2f6qyrZOZGf3Z0hDuSEo1XU95UAaQs/mtime:1582112622/sites/tutorial2program/files/shell-sort-0.2.png "First loop of Shell Sort")
3. In the second loop, an interval of `N/4 = 8/4 = 2` is taken and again the elements lying at these intervals are sorted.![Shell Sort step](https://cdn.programiz.com/cdn/farfuture/mWN26SdYDVUrjxrxkn_LMQAnuBMIOeK1Rafy8bOb-FQ/mtime:1582112622/sites/tutorial2program/files/shell-sort-0.3.png "Second Loop")Rearrange the elements at n/4 interval
   You might get confused at this point.![Shell Sort step](https://cdn.programiz.com/cdn/farfuture/8E8UaAuB56Z4ATHhsHvm5mtg_zfeTLXnwWuVT97DQc8/mtime:1582112622/sites/tutorial2program/files/shell-sort-0.4.png "Shell Sort steps")All the elements in the array lying at the current interval are compared.
   The elements at 4th and `2nd` position are compared. The elements at 2nd and `0th` position are also compared. All the elements in the array lying at the current interval are compared.
4. The same process goes on for remaining elements.![Shell Sort step](https://cdn.programiz.com/cdn/farfuture/D1p118uTKPJe0dW5hiapQSVzoclNdhjrlL8312Q9m7M/mtime:1619172539/sites/tutorial2program/files/shell-sort-step_4.png "Shell Sort steps")
5. Finally, when the interval is `N/8 = 8/8 =1` then the array elements lying at the interval of 1 are sorted. The array is now completely sorted.![Shell Sort step](https://cdn.programiz.com/cdn/farfuture/k4hVaQ09MUohD3kYSLzRMTCwsbW_DjarXxW2r-JVuHk/mtime:1619172531/sites/tutorial2program/files/shell-sort-step_5.png "Shell Sort steps")


## Complexity


| **Time Complexity** |   |
| - | - |
| Best | O(nlog n) |
| Worst | O(n^2^) |
| Average | O(nlog n) |
| **Space Complexity** | O(1) |
| **Stability** | No |



## Applications

Shell sort is used when:

* calling a stack is overhead. `uClibc` library uses this sort.
* recursion exceeds a limit. `bzip2` compressor uses it.
* Insertion sort does not perform well when the close elements are far apart. Shell sort helps in reducing the distance between the close elements. Thus, there will be less number of swappings to be performed.

## Other Sorting Algorithms

1. [Bubble Sort](https://www.programiz.com/dsa/bubble-sort)
2. [Quicksort](https://www.programiz.com/dsa/quick-sort)
3. [Insertion Sort](https://www.programiz.com/dsa/insertion-sort)
4. [Selection Sort](https://www.programiz.com/dsa/selection-sort)
