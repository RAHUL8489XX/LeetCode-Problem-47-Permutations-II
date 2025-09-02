# 🔁 LeetCode 47: Permutations II – Backtracking with Duplicate Filtering

This repository contains a Python solution to **LeetCode Problem 47: Permutations II**, where the goal is to generate all unique permutations of a list that may contain duplicate elements.

---

## 🧠 Problem Summary

Given an array `nums` that may contain **duplicate integers**, return **all unique permutations** of the array.

### Example:
```python
Input: nums = [1, 1, 2]
Output: [[1, 1, 2], [1, 2, 1], [2, 1, 1]]
```
## 📊 Complexity
Time Complexity: O(n! * n)
- Worst-case permutations with duplicate filtering

Space Complexity: O(n)
- Recursion stack + visited array
