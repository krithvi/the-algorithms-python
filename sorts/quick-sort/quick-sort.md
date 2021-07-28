## Problem Statement
Given an unsorted array of n elements, write a function to **sort** the array

## Approach
* Make the right-most index value pivot
* partition the array using pivot value
* quicksort left partition recursively
* quicksort right partition recursively

## Time Complexity
- O(n<sup>2</sup>) = Worst case performance
- O(n log n) = Best-case performance
- O(n log n) = Average performance

## Space Complexity
O(log n) = Worst case
