# CI/CD Demo

A simple JavaScript project demonstrating CI/CD best practices with automated testing using Jest.

## Description

This is a minimal demonstration project that shows how to set up a JavaScript project with continuous integration and continuous deployment practices. It includes basic math utility functions with comprehensive test coverage.

## Features

- Simple, reusable math utility functions
- Automated testing with Jest
- CI/CD ready project structure
- CommonJS module system

## Installation

Clone the repository:

```bash
git clone https://github.com/Latoure341/cicd-demo.git
cd cicd-demo
```

Install dependencies:

```bash
npm install
```

## Usage

Import the functions in your JavaScript files:

```javascript
const { add, subtract } = require('./index');

console.log(add(5, 3));       // Output: 8
console.log(subtract(10, 4)); // Output: 6
```

### Available Functions

- **`add(a, b)`** - Adds two numbers and returns the sum
- **`subtract(a, b)`** - Subtracts the second number from the first and returns the result

## Testing

Run the test suite:

```bash
npm test
```

This will run all tests in `index.test.js` using Jest and display the results.

## Project Structure

```
cicd-demo/
├── index.js          # Main module with utility functions
├── index.test.js     # Jest test file
├── package.json      # Project configuration and dependencies
└── README.md         # This file
```

## License

ISC

## Repository

https://github.com/Latoure341/cicd-demo
