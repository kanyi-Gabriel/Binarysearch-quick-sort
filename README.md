# Data Structure and Algorithms: Binary Search with Quicksort
This is a python demonstration of ho to perform **binary search** on unsorted array by first sorting it with **quicksort**

## Problem Statement
Given unsorted array and target value find the index of the target value using **binary search**. Use **quicksort** to sort the array before applying **iterative binary search**.

## 🔧 Algorithms Used

|Algorithm     | Purpose                  | Time Complexity  |
|--------------|--------------------------|------------------|
|Binary Search | Find the index of targets| O(log n)         |
|Quicksort     |Sort unsorted array       | O(n log n) avg   |

## 📦 Example Usage, We pass unsorted array and the corresponding target to get the index. Output is as shown

```python
Array: [64, 22, 76, 90, 100, 34, 125, 6, 89, 43, 150]
Targets: [56, 90, 43]

Sorted Array: [6, 22, 34, 43, 64, 76, 89, 90, 100, 125, 150]
Target 56 → Not found (-1)
Target 90 → Found at index 7
Target 43 → Found at index 3
