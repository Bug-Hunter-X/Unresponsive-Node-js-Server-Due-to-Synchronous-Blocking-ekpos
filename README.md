# Unresponsive Node.js Server Due to Synchronous Blocking

This repository demonstrates a common Node.js issue where a long-running synchronous operation blocks the event loop, causing the server to become unresponsive.  The `bug.js` file contains the problematic code, while `bugSolution.js` provides a solution using asynchronous operations.