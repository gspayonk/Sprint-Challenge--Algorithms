#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - we are asking individually, starting with n^2.


b) O(n^2) - checks once, then continues to check the same.


c) O(n) - same as above.

## Exercise II

Since we only have two cases when throwing the egg(s), the simplest (and most inefficient way) to test this would be to individually test the floors, starting from top to bottom until you find the f floor.

A more efficient way would be to test the floors in a block sort of form, if we throw the egg if it breaks we just need to check the floors below, if it doesn't we have another block above to check but not the one below. This would make the time complexity O(n), given that my proposed solution is done recursively.