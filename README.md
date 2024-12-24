# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is designed to increment a numerical field by a given value.  Attempting to use it with a non-numerical value results in an error.

## Bug
The `bug.js` file contains code that attempts to increment a field with a string value using the `$inc` operator. This will cause a MongoDB error.

## Solution
The `bugSolution.js` file provides the corrected code, where the value incremented is a valid number.  This illustrates the proper usage of the `$inc` operator.

## How to reproduce
1. Clone this repository.
2. Run the `bug.js` script. Observe the error.
3. Run the `bugSolution.js` script. Observe the successful update.