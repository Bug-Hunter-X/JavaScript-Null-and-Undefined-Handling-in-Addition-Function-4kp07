# JavaScript Null and Undefined Handling in Addition Function

This repository demonstrates a common JavaScript bug related to handling null and undefined values in a simple addition function. The original code lacks robustness in handling undefined inputs, leading to potential errors or unexpected outputs.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version with improved error handling and null/undefined checks. The solution demonstrates best practices for handling these cases and ensures more reliable function behavior.

## Bug Description:

The original function, `foo(a, b)`, correctly checks for null values. However, it omits checks for `undefined` values. This oversight can cause unexpected results or throw errors when either `a` or `b` is `undefined`. 

## Solution:

The improved function in `bugSolution.js` explicitly handles both `null` and `undefined` inputs, providing a more robust and reliable solution.