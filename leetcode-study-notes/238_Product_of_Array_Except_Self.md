***Key Points***

1/ Perform two traversals: one forward and one backward.
2/ Use a variable cur to temporarily store the running product.

First loop: Calculate the product of all elements to the left of each element.  
Second loop: Calculate the product of all elements to the right and directly update the result array.

Example: [1, 2, 3, 4]

res 1 1 2 6 (First Loop)  
res 24 12 8 6 (Second Loop)  
prefix 1 1 2 6 12  
postfix 24 24 12 4 1


