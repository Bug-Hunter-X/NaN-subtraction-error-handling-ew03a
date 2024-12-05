# JavaScript Subtraction with NaN Values

This repository demonstrates an uncommon bug in JavaScript related to the subtraction operator (-) when used with NaN (Not a Number) values.  The subtraction operation with NaN always results in NaN, regardless of the other operand, which can lead to unexpected behavior in applications that do not handle NaN values properly.  This can be particularly problematic in calculations where NaN propagation is not explicitly anticipated.

The `bug.js` file showcases the issue, while `bugSolution.js` presents ways to mitigate this behavior using robust error handling and NaN checks. 

The goal of this repo is to highlight a subtle but important aspect of JavaScript's numeric handling that can easily catch developers off-guard.