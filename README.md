# DSA-solutions
 #LeetCode-4
Median of Two Sorted Arrays
Problem

Find the median of two sorted arrays.

My Approach

I merged both sorted arrays into a single sorted array and then found the median by checking whether the total number of elements is odd or even.

Complexity
Time: O(m + n)
Space: O(m + n)
Note

This is my straightforward solution. I plan to learn and implement the optimal binary search approach with O(log(m + n)) time complexity in the future.




#GOG question-1
 Approach

- Used the **Sliding Window** technique with two pointers (`low` and `high`).
- Maintained the frequency of characters inside the current window using a `HashMap`.
- Expanded the window by moving `high` and adding characters to the map.
- If the number of distinct characters became greater than `k`, shrank the window by moving `low` until only `k` distinct characters remained.
- Whenever the window contained exactly `k` distinct characters, updated the maximum substring length.

### Time Complexity
- **O(n)**

### Space Complexity
- **O(k)** (for the `HashMap`)
# DSA-solutions
