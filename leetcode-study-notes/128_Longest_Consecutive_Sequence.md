**Tips:**

1. Set is better than map in this case.

2. Avoid timeouts:

**Comparison of two approaches:**

2.1) If you start by searching for the **maximum** value and then iteratively check for n-1, it will lead to redundant calculations.

2.2) Instead, start by finding the **minimum** value and iteratively search for n+1 while updating the length. Each number participates in at most one search and update, so the overall time complexity is O(n). This avoids duplicate processing and ensures linear time complexity.

2.3) Iterate through the set instead of the array to further save time.
