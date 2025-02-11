# Incorrect use of $inc operator in MongoDB update query

This example demonstrates an uncommon error that occurs when using the `$inc` operator in a MongoDB update query. The `$inc` operator is used to increment or decrement a numeric field by a specified value. However, if you provide a string value instead of a numeric value to `$inc`, MongoDB will throw an error or produce unexpected results.

The `bug.js` file contains the incorrect code that produces the bug.

The `bugSolution.js` file demonstrates the correct way to use the `$inc` operator in a MongoDB update query.