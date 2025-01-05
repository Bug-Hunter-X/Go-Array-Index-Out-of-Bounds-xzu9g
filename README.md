# Go Array Index Out of Bounds

This repository demonstrates a common error in Go: an array index out of bounds.  The provided `bug.go` file contains a loop that attempts to access an array element beyond its valid index range.  This results in a runtime panic.

The `bugSolution.go` file shows the corrected code with the loop condition modified to prevent the index out of bounds error.  The solution highlights proper array index handling in Go.

This example serves as a reminder to carefully check loop conditions and array bounds to avoid unexpected runtime errors.