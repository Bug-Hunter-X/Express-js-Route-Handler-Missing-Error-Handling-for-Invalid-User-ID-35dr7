# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.

The `bug.js` file contains code that attempts to retrieve a user from an array based on their ID. However, it fails to handle cases where the ID is not a valid number, leading to potential crashes or unexpected behavior.

The `bugSolution.js` file provides a corrected version with improved error handling.