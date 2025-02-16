# Off-by-One Error in Java Array
This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error causes an `ArrayIndexOutOfBoundsException` because the loop attempts to access an element beyond the array's bounds.  The solution shows the correct way to iterate to avoid this issue.

## Bug
The `bug.java` file contains the erroneous code.  The loop iterates one element past the end of the array, leading to an exception.

## Solution
The `bugSolution.java` file shows the corrected code. The loop condition is changed to properly iterate within the bounds of the array.
