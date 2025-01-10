# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a number.  The `bug.js` file shows the erroneous code, while `bugSolution.js` provides the correct implementation.

The error arises from attempting to increment a field with a string value, which is not a valid numerical operation. The solution involves ensuring the value passed to `$inc` is a number.

## Bug:
Incorrect usage of the `$inc` operator in a MongoDB update operation, leading to an error.