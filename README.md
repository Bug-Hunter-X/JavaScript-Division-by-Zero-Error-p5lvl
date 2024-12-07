# JavaScript Division by Zero Bug

This repository demonstrates a common error in JavaScript: division by zero. The `foo` function attempts to divide `a` by `b`, but does not handle the case where `b` is 0. This results in an error.

## Bug

The bug is in the `foo` function. If the second argument (`b`) is 0, the function throws an error.

## Solution

The solution is to add a check to ensure that `b` is not 0 before performing the division. The updated function includes this check and returns 0 if `b` is 0 to prevent the error.

## How to run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a code editor.
3. Run the JavaScript files using a Node.js runtime or in a browser's console to see the bug and its solution in action.