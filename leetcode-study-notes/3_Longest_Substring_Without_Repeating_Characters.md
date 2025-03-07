***Sliding Window***  

My original approach returned to a wrong index.  

The correct approach is:  

Once a duplicated character is found, move the left edge of the window until there are no duplicates left within the window.  