***Two Pointers***

1/ Deduplication method:  

The way to remove duplicates differs between the first number and the second/third numbers. Reason: The same number can appear in different combinations, but the same combination should not appear more than once.  

2/ Timing of deduplication:  

The second and third numbers should be deduplicated only after a valid combination is found; otherwise, correct answers may be skipped.  

3/ Time Complexity：

Arrays.sort() takes O(n log n);
(*for* + *while*) takes O(n^2);

So the final TC is O(n^2).

4/ Space Complexity：

Not including the output: O(1)