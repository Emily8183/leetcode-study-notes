***Greedy Approach:***

Think about the key factor: the height remains limited by the shorter one!

Start from the two ends, keep moving the pointer pointing to the shorter height toward the center (because moving the taller pointer won’t help.)

We can dynamically calculate the area and find the max value. 

1/ O(n) time complexity
2/ Operates in place, O(1) SC