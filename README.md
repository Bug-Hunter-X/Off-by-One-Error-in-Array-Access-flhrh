# Off-by-One Error in Go
This repository demonstrates a common off-by-one error in Go that can lead to runtime panics. The error occurs when accessing elements of an array using a loop that does not correctly account for the zero-based indexing of arrays.
The `bug.go` file contains the erroneous code, and the `bugSolution.go` file demonstrates the correct implementation that addresses the error.