# Null Value Handling in JavaScript Function
This repository demonstrates an uncommon bug related to handling null values in a JavaScript function and its solution.

## Bug Description
The function `foo` is designed to process two arguments (`a` and `b`). However, it fails to handle cases where one or both of the arguments are null, leading to unexpected behavior or errors.

## Solution
The solution involves explicitly checking for null values at the beginning of the function and handling them appropriately.  This ensures that the function operates correctly even when null values are passed.

## How to reproduce the bug
1. Clone this repository.
2. Open `bug.js` and observe the function `foo`.
3. Call the function with null values for the arguments and note the output.

## How to fix the bug
1. Review the code in `bugSolution.js` which incorporates a null check.
2. Notice how the null check gracefully returns null without errors or unexpected behavior.
