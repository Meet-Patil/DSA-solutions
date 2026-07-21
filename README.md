# DSA-solutions

## LeetCode-4: Median of Two Sorted Arrays

### Problem
Find the median of two sorted arrays.

### My Approach
I merged both sorted arrays into a single sorted array and then found the median by checking whether the total number of elements is odd or even.

### Complexity
- **Time:** O(m + n)
- **Space:** O(m + n)

### Note
This is my straightforward solution. I plan to learn and implement the optimal binary search approach with **O(log(m + n))** time complexity in the future.

---

## GFG Question 1: Longest Substring with K Unique Characters

### Approach
- Used the **Sliding Window** technique with two pointers (`low` and `high`).
- Maintained the frequency of characters using a `HashMap`.
- Expanded the window by moving `high`.
- Shrank the window whenever the number of distinct characters exceeded `k`.
- Updated the maximum length whenever the window contained exactly `k` distinct characters.

### Complexity
- **Time:** O(n)
- **Space:** O(k)
