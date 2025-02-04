# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: a `TypeError` thrown when attempting to access the `length` property of an undefined variable.  The example code shows the error and how to implement a robust solution that handles both null and undefined inputs.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` to observe the error-producing code.
3. Run `bug.js` in a Node.js environment or a web browser's console.
4. Observe the error message in the console.
5. Open `bugSolution.js` to see the improved code that handles null and undefined inputs.

## Bug Solution

The `bugSolution.js` file provides a corrected function that first checks if the input is either null or undefined before attempting to access the `length` property.