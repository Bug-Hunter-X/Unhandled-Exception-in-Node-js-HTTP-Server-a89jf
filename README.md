# Unhandled Exception in Node.js HTTP Server

This repository demonstrates an example of an unhandled exception in a Node.js HTTP server and how to properly handle it.

## Bug

The `bug.js` file contains a simple HTTP server that throws an unhandled exception.  This causes the server to crash without any graceful handling of the error.

## Solution

The `bugSolution.js` file shows the correct way to handle exceptions using a `try...catch` block, ensuring the server doesn't crash and can potentially log the error or send a proper error response to the client.

## How to Reproduce

1. Clone the repository.
2. Run `node bug.js`.
3. Observe that the server crashes immediately.
4. Run `node bugSolution.js`.
5. The server will now handle the error gracefully. 