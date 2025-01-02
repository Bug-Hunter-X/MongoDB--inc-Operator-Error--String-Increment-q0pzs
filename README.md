# MongoDB $inc Operator Error: String Increment
This repository demonstrates an incorrect usage of the `$inc` operator in MongoDB, specifically attempting to increment a counter field with a string value.

The `$inc` operator is used to increment a numeric field by a specified value.  Using a string value results in an error.

The `bug.js` file shows the incorrect implementation. The `bugSolution.js` file shows the corrected implementation.

## How to Reproduce
1.  Ensure you have a MongoDB instance running.
2.  Create a collection called `myCollection` with a document containing a numeric `counter` field.
3.  Run the code in `bug.js`.
4. Observe the error.
5. Run the code in `bugSolution.js` to see the corrected behaviour.
