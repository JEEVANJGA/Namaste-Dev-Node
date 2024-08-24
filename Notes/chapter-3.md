# Node.js - Let's Write Code

## Installation

1. **Install Node.js**: Use the `nvm` (Node Version Manager) package manager. Check the [official documentation](https://github.com/nvm-sh/nvm) for detailed instructions.
2. **Verify Installation**: After installation, check the Node.js version by running: `node -v`
3. **Check npm Version**: Run `npm -v` to get the version of the Node.js package manager.

## Node REPL

REPL stands for Read, Evaluate, Print, Loop.

- **Start REPL**: Open your terminal and type `node` to enter the Node REPL.
- **Execute Code**: Within this loop, you can write and execute any JavaScript code.

Node.js is a JavaScript runtime environment.

## Global Object

### Browser vs Node.js

- **Browser**: The global object in a browser is `window`.
- **Node.js**: The global object in Node.js is `global`.

### Features

- The global object provides access to several JavaScript features like `setTimeout`, `setInterval`, etc.
- Note that `global` is not a V8 feature.

### `this` Keyword

- **Browser**: In a browser, `this` returns the `window` object.
- **Node.js**: In Node.js, `this` returns an empty object.

### `globalThis`

- `globalThis` is a common global object across all JavaScript environments.

## Additional Information - gathered on research

### Node.js Modules

- **CommonJS**: Node.js uses the CommonJS module system. You can import modules using `require` and export them using `module.exports`.
- **ES Modules**: Node.js also supports ES Modules. You can import modules using `import` and export them using `export`.

### Asynchronous Programming

- **Callbacks**: Node.js heavily uses callbacks for asynchronous operations.
- **Promises**: Promises provide a cleaner way to handle asynchronous operations.
- **async/await**: `async` and `await` keywords allow writing asynchronous code in a synchronous manner.

### Event Loop

- Node.js uses an event-driven, non-blocking I/O model. The event loop is a core concept that handles asynchronous operations.

### File System

- Node.js provides a `fs` module to interact with the file system. You can read, write, and manipulate files using this module.

### HTTP Module

- Node.js has a built-in `http` module to create web servers and handle HTTP requests and responses.

### Package Management

- **npm**: The default package manager for Node.js.
- **yarn**: An alternative package manager that can be used with Node.js.

### Debugging

- Use the `node --inspect` flag to start the Node.js application in debug mode.
- You can also use the built-in debugger in Visual Studio Code for debugging Node.js applications.

### Best Practices

- **Error Handling**: Always handle errors in asynchronous code.
- **Code Style**: Follow a consistent code style. Use tools like ESLint to enforce coding standards.
- **Security**: Keep your dependencies up to date and use tools like `npm audit` to check for vulnerabilities.

By following these guidelines and understanding the core concepts, you can effectively write and manage Node.js applications.