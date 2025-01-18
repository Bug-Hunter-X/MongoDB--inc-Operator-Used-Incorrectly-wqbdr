# MongoDB $inc Operator Usage Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value, but it can throw errors if used with non-numeric values.

## Bug
The original code attempts to increment the `field` in `myCollection` with a string value, which is incorrect. This leads to an error.

## Solution
The solution corrects this error by ensuring that the value used with `$inc` is a number. 