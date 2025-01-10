# Node.js Server Port Already in Use

This repository demonstrates a common error in Node.js: attempting to start a server on a port that is already in use.

The `server.js` file contains the buggy code, while `serverSolution.js` provides a solution.

## Bug

The `server.js` file attempts to start an HTTP server on port 8080. If another application is already using this port, the server will fail to start and throw an error.

## Solution

The `serverSolution.js` file demonstrates a more robust solution by using the `listen` method's callback function to handle potential errors.