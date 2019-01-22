# VScode-Nodejs-Express-boilerplate
For starting a Node.js Express Webapp with helpful boilerplate code. 
Run the test server locally with script "npm run debug".

Contains two vscode debugging configurations:

- Server side debugging by attaching to a running node process
- Client side debugging by using the "Debugger for Chrome" extension

Thus all code can be debugged in vscode with breakpoints.

NOTE: Breakpoints will only be bound for server side code using the first debug configuration and vice versa for client side code. Currently, no way exists to have breakpoints bound simultaneously in client and server side code. Also ensure "Debugger for Chrome" extension is installed for the second debug configuration to function.
