# MongoDB $inc operator with non-numeric value
This example demonstrates an uncommon error in MongoDB when using the `$inc` operator with a non-numeric value.  The `$inc` operator is used to increment a numeric field by a specified value. However, if you provide a non-numeric value, MongoDB will throw an error or produce an unexpected result.

The example showcases the incorrect usage of the `$inc` operator with a string value. The solution demonstrates the correct usage by supplying a numeric value.