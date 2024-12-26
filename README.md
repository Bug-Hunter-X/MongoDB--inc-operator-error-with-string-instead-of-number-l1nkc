# MongoDB $inc operator error with string instead of number

This example demonstrates an uncommon error that can occur when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, if you attempt to increment a field using a string value instead of a number, you'll encounter unexpected results.  The solution will provide the correct implementation.

## Bug Report:
The bug arises from passing a string value ('1') instead of a number (1) to the $inc operator. This results in the field not being properly incremented.