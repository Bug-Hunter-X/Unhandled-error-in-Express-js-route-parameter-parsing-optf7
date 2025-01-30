# Unhandled Error in Express.js Route Parameter Parsing

This repository demonstrates a common error in Express.js applications: failing to handle potential errors when parsing route parameters.  Specifically, the example code attempts to parse a user ID from the route parameters without checking if the ID is a valid integer.  This can lead to unexpected behavior or even crashes if the ID is not a number.

The `bug.js` file shows the buggy code, while `bugSolution.js` provides a corrected version with robust error handling.