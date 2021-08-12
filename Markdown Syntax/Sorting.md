# Types of Sorting Algorithms

## Table of Contents

- [Types of Sorting Algorithms](#types-of-sorting-algorithms)
  - [Table of Contents](#table-of-contents)
  - [How to optimize a code](#how-to-optimize-a-code)
  - [Bubble Sort](#bubble-sort)
    - [Normal Bubble Sort](#normal-bubble-sort)
    - [Optimized Bubble Sort](#optimized-bubble-sort)
  - [Insertion Sort](#insertion-sort)

## How to optimize a code

1. Try using flag.
2. Use byte for flag. and small data types for small ranges.

## Bubble Sort

### Normal Bubble Sort

Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order.


### Optimized Bubble Sort

The above function always runs O(n^2) time even if the array is sorted. It can be optimized by stopping the algorithm if inner loop didn’t cause any swap.

by using flag varable.

References :

https://www.geeksforgeeks.org/bubble-sort/

https://youtu.be/o4bAoo_gFBU

https://www.studytonight.com/data-structures/bubble-sort

https://en.wikipedia.org/wiki/Bubble_sort

Worst and Average Case Time Complexity: O(n*n). Worst case occurs when array is reverse sorted.
Best Case Time Complexity: O(n). Best case occurs when array is already sorted.
Auxiliary Space: O(1)
Boundary Cases: Bubble sort takes minimum time (Order of n) when elements are already sorted.
Sorting In Place: Yes
Stable: Yes

**Worst complexity :** n^2
**Average complexity :** n^2
**Best complexity :** n
**Space complexity :** 1
**Method :** Exchanging
**Stable :** Yes
**Class :** Comparison sort
:*

## Insertion Sort

https://www.geeksforgeeks.org/insertion-sort/

https://youtu.be/yCxV0kBpA6M

Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.

Time Complexity: O(n^2) 
Auxiliary Space: O(1)
Boundary Cases: Insertion sort takes maximum time to sort if elements are sorted in reverse order. And it takes minimum time (Order of n) when elements are already sorted.
Algorithmic Paradigm: Incremental Approach
Sorting In Place: Yes
Stable: Yes
Online: Yes
Uses: Insertion sort is used when number of elements is small. It can also be useful when input array is almost sorted, only few elements are misplaced in complete big array.

Worst complexity: n^2
Average complexity: n^2
Best complexity: n
Space complexity: 1
Method: Insertion
Stable: Yes
Class: Comparison sort