# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error arises from an incorrect loop condition that attempts to access an index beyond the array's bounds.

## Bug Description
The provided Java code attempts to populate an integer array with even numbers. However, the loop condition `i <= arr.length` in `bug.java` leads to an `ArrayIndexOutOfBoundsException`.  Array indices in Java are zero-based; therefore, the correct condition should be `i < arr.length`.

## Solution
The `bugSolution.java` file provides a corrected version of the code with the corrected loop condition.