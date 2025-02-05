# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numeric field by a specified value. However, providing a string value instead of a number results in an unexpected behavior or error.

## Bug Description
The original code attempts to increment the `field` by '1' (string).  This leads to unexpected results rather than correctly incrementing the field.

## Solution
The solution corrects this by providing the increment value as a number (1) instead of a string ('1').