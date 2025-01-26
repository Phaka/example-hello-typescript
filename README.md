# Hello World in TypeScript

A minimal "Hello, World!" implementation in TypeScript. TypeScript extends JavaScript by adding static type checking while remaining fully compatible with JavaScript code. It was developed by Microsoft to help build large-scale JavaScript applications.

## Installation

TypeScript requires Node.js to be installed first. Once Node.js is installed, TypeScript can be installed via npm:

```bash
npm install -g typescript
```

This installs the TypeScript compiler (`tsc`) globally on your system.

## Building and Running

TypeScript needs to be compiled to JavaScript before it can be run. The process involves two steps:

```bash
# Compile TypeScript to JavaScript
tsc main.ts

# Run the resulting JavaScript with Node.js
node main.js
```

You can also run TypeScript directly using `ts-node`:

```bash
# Install ts-node
npm install -g ts-node

# Run TypeScript directly
ts-node main.ts
```

## Code Explanation

The program demonstrates some key aspects of TypeScript:

1. The syntax is identical to JavaScript for this simple case, showing TypeScript's compatibility
2. While TypeScript supports static typing, type annotations are optional when types can be inferred
3. TypeScript files use the `.ts` extension instead of JavaScript's `.js`
4. The code compiles to standard JavaScript that can run in any JavaScript environment

The compilation step transforms our TypeScript code into equivalent JavaScript, performing type checking in the process. This provides development-time type safety while maintaining runtime compatibility with the JavaScript ecosystem.
