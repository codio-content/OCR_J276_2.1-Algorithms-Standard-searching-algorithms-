A binary search compares the search item with the **median** item in a list, repeatedly splitting the list in half until the item is found or there are no more items left to search.

It is a ‘divide and conquer’ algorithm as it increases efficiency by repeatedly splitting the list into two – so halving the problem.

The median is the **middle** item. If there are an odd number of items in the list then the median item is obvious e.g. if there are 13 items then the median is the 7th as there will be 6 on either side.

But if there are 12 items the mathematical median is 6.5 but in the list there are two medians – the 6th and the 7th.
You can use whichever one you want as long as you are consistent.


Here is the algorithm:

1. Select the middle item (the median).
1. Compare this value with the search criterion. 
1. If they are equal, then stop.
1. If the search criterion is lower, then repeat 1 and 2 with the left-hand side of the list.
1. If it is higher, then repeat 1 and 2 with the right-hand side of the list.
1. Repeat these steps until the search criterion is found or there are no more items in the list to search.






Have a look at this video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/iDVH3oCTc2c" frameborder="0" allowfullscreen></iframe>
