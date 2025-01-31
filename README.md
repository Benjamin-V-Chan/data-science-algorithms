# data-science-algorithms

## **Overview**
This project contains implementations of various sorting algorithms in Python. Each algorithm sorts numerical datasets using different approaches, demonstrating a range of efficiencies and use cases.

## **Sorting Algorithms Implemented**
- **Bubble Sort** – Simple but inefficient comparison-based sorting.
- **Selection Sort** – Finds the smallest element and swaps it in place.
- **Insertion Sort** – Builds a sorted list one element at a time.
- **Merge Sort** – Efficient divide-and-conquer sorting method.
- **Quick Sort** – Uses a pivot to recursively sort subarrays.
- **Heap Sort** – Utilizes a binary heap for efficient sorting.

## **Installation**
No external dependencies are required. Ensure you have Python installed.

## **Usage**
Import and call any sorting function with a list of numbers:
```python
from sorting_algorithms import quick_sort

arr = [10, 3, 8, 15, 2]
print("Sorted array:", quick_sort(arr))
```

Alternatively, run the test function to compare all sorting methods:
```python
from sorting_algorithms import test_sorting_algorithms

test_sorting_algorithms()
```