📌Optimization:  
First loop: Calculate the product of all elements to the left of each element.  
Second loop: Calculate the product of all elements to the right and directly update the result array.

Example: [1, 2, 3, 4]

res 1 1 2 6 (First Loop)
res 24 12 8 6 (Second Loop)
prefix 1 1 2 6 12
postfix 24 24 12 4 1

---

📌Solution:
If the current asteroid is positive, there's no need to compare it with the top of the stack.

- If the stack's top is positive, they're moving in the same direction (no collision).
- If the stack's top is negative, the top asteroid is moving LEFT, and the current asteroid is moving right, so no collision occurs.

Comparisons are **ONLY** required when the current asteroid is negative.

---

📌Tips:

1. Pay attention to whether the loop iterates over indexes or the elements themselves.

2. range(len(nums)-1, -1, -1):
   len(nums)-1: The starting point is the last index of the list.
   -1: The ending value is -1, but remember that the stop value is exclusive, so this range will decrement from index 3 down to 0 (excluding -1).
   step = -1: The step size is -1, meaning the loop decreases by 1 each iteration.
