# Day 4 — Prefix Sum & Sliding Window Patterns

## Overview
Day 4 introduced range-based array processing techniques.  
The focus was on eliminating repeated computations by maintaining cumulative and running state across subarrays.

These patterns form the foundation for solving medium-level array interview problems.

---

## Topics Covered

- Prefix sum arrays  
- Range sum queries  
- Kadane’s algorithm for maximum subarray sum  
- Fixed-size sliding window technique  
- Running sum optimization  

---

## Problems Solved

### 1. 1-D Prefix Sum
Constructed prefix sum array to enable efficient cumulative calculations.

**Key Concept:** Cumulative aggregation  
**Time Complexity:** O(n)  
**Space Complexity:** O(n)

---

### 2. Range Sum Query
Computed sum of elements between given indices.

**Key Concept:** Brute-force range calculation  
**Time Complexity:** O(n)

---

### 3. Maximum Subarray Sum (Kadane’s Algorithm)
Found maximum sum of any contiguous subarray.

**Key Concept:** Dynamic decision to extend or restart subarray  
**Time Complexity:** O(n)  
**Space Complexity:** O(1)

---

### 4. Maximum Sum Subarray of Size K
Determined the maximum sum of fixed-length subarrays using sliding window.

**Key Concept:** Window sum update by add–remove strategy  
**Time Complexity:** O(n)  
**Space Complexity:** O(1)

---

## Challenges Faced

- Correct initialization in Kadane’s algorithm  
- Distinguishing between restarting and extending subarrays  
- Managing running sums without recomputation  

---

## Learnings

- Prefix sums remove repeated summation loops  
- Kadane’s algorithm is dynamic programming in linear time  
- Sliding window is essential for fixed-range optimization  
- Proper initialization prevents negative-array edge case failures  

---

## Outcome

Successfully implemented prefix sum, Kadane’s algorithm, and sliding window problems.  
Developed strong understanding of subarray processing patterns.

---

## Next Step

Proceed to Day 5:
- Variable-size sliding window  
- Subarray sum equals K  
- Longest subarray problems  

Core range-processing patterns established.
