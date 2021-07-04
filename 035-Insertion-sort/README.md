# Insertion Sort

Insertion sort is [a sorting algorithm](https://www.programiz.com/dsa/sorting-algorithm) that places an unsorted element at its suitable place in each iteration.

Insertion sort works similarly as we sort cards in our hand in a card game.

We assume that the first card is already sorted then, we select an unsorted card. If the unsorted card is greater than the card in hand, it is placed on the right otherwise, to the left. In the same way, other unsorted cards are taken and put in their right place.

A similar approach is used by insertion sort.


## Working of Insertion Sort

Suppose we need to sort the following array.

1. The first element in the array is assumed to be sorted. Take the second element and store it separately in `key`.

Compare `key` with the first element. If the first element is greater than `key`, then key is placed in front of the first element. If the first element is greater than key, then key is placed in front of the first element.

2. Now, the first two elements are sorted.

Take the third element and compare it with the elements on the left of it. Placed it just behind the element smaller than it. If there is no element smaller than it, then place it at the beginning of the array.

3. Similarly, place every unsorted element at its correct position.


## Complexity


| **Time Complexity** |   |
| - | - |
| Best | O(n) |
| Worst | O(n^2^) |
| Average | O(n^2^) |
| **Space Complexity** | O(1) |
| **Stability** | Yes |


## Applications

The insertion sort is used when:

* the array is has a small number of elements
* there are only a few elements left to be sorted

## Similar Sorting Algorithms

1. [Bubble Sort](https://www.programiz.com/dsa/bubble-sort)
2. [Quicksort](https://www.programiz.com/dsa/quick-sort)
3. [Merge Sort](https://www.programiz.com/dsa/merge-sort)
4. [Selection Sort](https://www.programiz.com/dsa/selection-sort)
