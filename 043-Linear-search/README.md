# Linear Search

Linear search is a sequential searching algorithm where we start from one end and check every element of the list until the desired element is found. It is the simplest searching algorithm.


## How Linear Search Works?

The following steps are followed to search for an element `k = 1` in the list below.

![Initial array](https://cdn.programiz.com/sites/tutorial2program/files/linear-search-initial-array.png "Linear Search Array")Array to be searched for1. Start from the first element, compare k with each element x.![Element not found](https://cdn.programiz.com/sites/tutorial2program/files/linear-search-comparisons.png "Linear Search")

1. If `x == k`, return the index.![Element found](https://cdn.programiz.com/sites/tutorial2program/files/linear-search-found.png "Linear Search")
2. Else, return not found.


## Complexities

**Time Complexity:** `O(n)`

**Space Complexity:** `O(1)`

## Applications

1. For searching operations in smaller arrays (<100 items).
