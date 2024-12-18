# Unhandled Promise Rejection in Express.js
This repository demonstrates a common error in Node.js asynchronous programming: unhandled promise rejections.  The `bug.js` file contains code that simulates an asynchronous operation that might fail.  The error is not properly handled, leading to an unhandled promise rejection.  The solution is provided in `bugSolution.js`, which correctly handles potential errors using try...catch blocks and proper error handling middleware in Express.js.

## How to Reproduce
1. Clone this repository.
2. Navigate to the repository directory.
3. Run `npm install express` to install the necessary dependencies.
4. Run `node bug.js`. You should see an unhandled promise rejection error in the console. 
5. Run `node bugSolution.js`. This will gracefully handle the error and not throw an unhandled promise rejection. 
