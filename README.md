# Missing Return Statement in MATLAB Function

This repository demonstrates a common error in MATLAB functions: a missing return statement in an `if-elseif-else` block. This can lead to unexpected behavior and difficult-to-debug issues.

The `bug.m` file contains the erroneous function. The `bugSolution.m` file provides the corrected version.

## Bug Description:

The `myFunction` function uses an `if-elseif-else` block to handle different conditions. However, the `else` block does not have a return statement, potentially leading to an incorrect return value.

## How to reproduce the bug:

Run the `bug.m` file. Observe the unexpected output when the condition in the `else` block is met.

## How to fix the bug:

Refer to the `bugSolution.m` file for the corrected version. A `return` statement has been added to the `else` block to ensure the function always returns a value.