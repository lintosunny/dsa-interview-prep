# Data Structures & Algorithms Prep for ML/AI Engineers

This repository is a structured collection of **Data Structures and Algorithms (DSA)** problems, organized by **problem-solving patterns**. It is designed to help **ML Engineers, AI Engineers, and MLEs** build strong problem-solving skills for coding interviews.  

## Why This Repo?
- Focused on **problem-solving patterns** rather than random problems.  
- Covers **essential topics** needed for ML/AI/Software Engineering interviews.  
- Includes **LeetCode references** for practice.  
- Easy-to-navigate **folder structure** with consistent naming.  

## Problem-Solving Patterns

| # | **Topic**        | **Pattern**             | **Description** | **Example Questions** |
|---|------------------|-------------------------|-----------------|-----------------------|
| 1 | Arrays & Strings | Sliding Window          | Maintain a moving window (subarray/substring) for sum/unique chars problems. | LC 53: Max Subarray, LC 3: Longest Substring Without Repeating Chars, LC 76: Minimum Window Substring |
| 2 | Arrays & Strings | Two Pointers            | Use left/right pointers to shrink/expand range. Good for sorted arrays, strings. | LC 167: Two Sum II, LC 283: Move Zeroes, LC 125: Valid Palindrome |
| 3 | Arrays & Strings | Prefix Sum              | Precompute running sums to answer subarray/range queries efficiently. | LC 560: Subarray Sum Equals K, LC 303: Range Sum Query |
| 4 | Hashmaps         | Frequency Map           | Count frequency of elements, chars, substrings. | LC 1: Two Sum, LC 242: Valid Anagram, LC 49: Group Anagrams |
| 5 | Hashmaps         | Hash + Sliding Window   | Track counts inside a window. | LC 340: Longest Substring with K Distinct Chars, LC 76: Minimum Window Substring |
| 6 | Hashmaps         | Prefix Sum + Hashmap    | Store prefix sums in hashmap to find subarray sums. | LC 560: Subarray Sum Equals K, LC 523: Continuous Subarray Sum |
| 7 | Sorting          | Divide & Conquer        | Implement merge sort, quick sort. | LC 912: Sort an Array, LC 56: Merge Intervals |
| 8 | Sorting          | Sorting + Two Pointers  | After sorting, use two pointers to solve sum/interval problems. | LC 15: 3Sum, LC 986: Interval List Intersections |
| 9 | Sorting          | Bucket/Counting Sort    | Special-case sorting for limited ranges. | LC 75: Sort Colors, LC 347: Top K Frequent Elements |
| 10 | Binary Search   | Standard Binary Search  | Search in sorted array/logarithmic search space. | LC 704: Binary Search, LC 35: Search Insert Position |
| 11 | Binary Search   | Lower/Upper Bound       | Find first/last occurrence. | LC 278: First Bad Version, LC 34: Find First and Last Position |
| 12 | Binary Search   | Binary Search on Answer | Search space is the answer (e.g., min/max capacity). | LC 875: Koko Eating Bananas, LC 1011: Capacity to Ship Packages |
| 13 | Binary Search   | Rotated Sorted Array    | Apply binary search with pivot logic. | LC 33: Search in Rotated Sorted Array |
| 14 | Linked Lists    | Fast & Slow Pointers    | Use two speeds to detect cycles or find middle. | LC 141: Linked List Cycle, LC 876: Middle of Linked List |
| 15 | Linked Lists    | Dummy Node Technique    | Use dummy node for clean merges/deletions. | LC 206: Reverse Linked List, LC 21: Merge Two Sorted Lists |
| 16 | Stacks & Queues | Monotonic Stack         | Maintain increasing/decreasing stack for next greater/smaller element. | LC 496: Next Greater Element, LC 739: Daily Temperatures |
| 17 | Stacks & Queues | BFS with Queue          | Level-order traversal, shortest paths in grids. | LC 102: Binary Tree Level Order Traversal, LC 1091: Shortest Path in Binary Matrix |
| 18 | Stacks & Queues | Stack for Expressions   | Parse/validate expressions (parentheses, eval). | LC 20: Valid Parentheses, LC 155: Min Stack |
| 19 | Heaps           | Top-K Elements          | Use heap to track k largest/smallest. | LC 215: Kth Largest Element, LC 347: Top K Frequent Elements |
| 20 | Heaps           | Heap + Sorting          | Merge multiple sorted lists/arrays. | LC 23: Merge k Sorted Lists, LC 295: Find Median from Data Stream |

## How to Use
1. Pick a **pattern**.  
2. Read the **description** in `README.md`.  
3. Open the corresponding folder and start solving problems.  
4. Practice on LeetCode (links provided in the table).  

## Goals
- Strengthen **DSA foundation** for ML/AI Engineer interviews.  
- Learn to identify and apply **problem-solving patterns**.  
- Build confidence in **coding interviews**.  

## Notes
- Problems are solved in **Python** (can extend to other languages).  
- Each solution is named after its **LeetCode problem** (`two-sum.py`, `merge-intervals.py`).  
- Contributions welcome! Feel free to add problems/solutions.  

## Resources
- [LeetCode](https://leetcode.com/)  
- [NeetCode.io](https://neetcode.io/)  
- [Interviewing.io](https://interviewing.io/)  

💡 *Conquering algorithms, one pattern at a time.*  
