# Unhandled Errors in Node.js HTTP Server

This repository demonstrates a common error in Node.js: the lack of error handling in an HTTP server.  The `bug.js` file contains the problematic code, while `bugSolution.js` provides a corrected version with robust error handling.

The original code creates a simple HTTP server but fails to handle potential errors during server creation or listening on a port. This can lead to unexpected crashes and a lack of informative error messages.

The solution incorporates proper error handling using the `'error'` event listener, providing more graceful error management and more informative logging for debugging purposes.