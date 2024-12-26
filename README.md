# Unhandled Database Error in Express.js Route Handler

This repository demonstrates a common error in Express.js applications: the lack of proper error handling within route handlers, specifically when interacting with databases.  The `bug.js` file shows an example where a database query (simulated) could throw an error, causing the server to crash without providing any informative error message to the client. The `bugSolution.js` file offers a corrected implementation with improved error handling.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies (none are strictly required for this example).
3. Run `node bug.js`.  Try to access a route that would simulate a database error. The server will likely crash without a helpful error message.
4. Run `node bugSolution.js` to see the improved error handling.