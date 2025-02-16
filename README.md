# Ada Array Slice Assignment Bug

This repository demonstrates a common error in Ada programming related to assigning array slices.  When a slice of an array is assigned to another array, Ada's strong typing and bounds checking can lead to a `Constraint_Error` if the destination array isn't large enough to hold the slice.

The `bug.ada` file contains the erroneous code, while `bugSolution.ada` provides the corrected version.  The solution illustrates how to correctly handle array slice assignment, avoiding the `Constraint_Error`.

This is a common issue for beginners in Ada, highlighting the importance of understanding Ada's array handling.