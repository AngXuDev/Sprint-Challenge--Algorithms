#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) - a has to catch up to n^3 while only getting n^2 each loop through the while, so it will take n turns to get from n^2 to n^3

b) O(n^2) - nested while loop within a for loop

c) O(n) - because we're subtracting 1 each recursive call, the recursive function will run 'bunnies' times until reaching base

## Exercise II

Go to the middle floor of the building (n/2) and drop your first egg, if the egg breaks when you drop it, go halfway down to the first floor and try again. If the egg doesn't break, go halfway up to the top floor and try again. Time complexity should be O(log n) since this is basically binary search
