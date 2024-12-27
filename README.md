# Unexpected Zero Value Initialization in Go

This repository demonstrates a subtle bug in Go related to the implicit zero initialization of variables.  The code in `bug.go` incorrectly assumes the variable `i` is initialized to a value other than zero before using it in a calculation. This can lead to incorrect results.

The solution in `bugSolution.go` shows how to correctly initialize `i` before its use in the calculation.  Pay close attention to how different initialization methods impact the result and prevent unexpected behavior.