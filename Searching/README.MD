# Searching Algorithms

## Linear Search Algorithm

Linear search checks each element of an array or list sequentially until the target element is found or the end of the array is reached.  

- **Time Complexity:** O(n)  
- **Space Complexity:** O(1)  
- Works on both **sorted and unsorted arrays**.  

---

## Binary Search Algorithm

Binary search is a **searching algorithm** used to find the position of a target element in a **sorted array or list**. It works by **repeatedly dividing the search range in half**:

1. Compare the target with the middle element.  
2. If the target equals the middle element, the search is complete.  
3. If the target is smaller, repeat the search on the left half.  
4. If the target is larger, repeat the search on the right half.  

- **Requirement:** The array must be sorted.  
- **Time Complexity:**  
  - Best case: O(1)  
  - Average/Worst case: O(log n) — much faster than linear search for large arrays.  
- **Space Complexity:** O(1) for iterative implementation; O(log n) for recursive implementation.  
- **Type:** Divide-and-conquer algorithm.  

---

### Reasons Binary Search Can Fail

1. Array is not sorted (breaks the core logic).  
2. Incorrect calculation of `mid`, `low`, or `high`.  
3. Presence of duplicates (may require modified binary search for first/last occurrence).  

---

### Notes

- Iterative binary search is **preferred for real-world applications** due to lower memory usage.  
- Recursive binary search is elegant and easy to understand but uses additional stack memory.
