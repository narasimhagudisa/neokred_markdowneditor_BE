# Node.js TypeScript Project

## Overview
This is a Node.js application written in TypeScript. The project includes scripts for development, building, linting, and running the application.

## Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (latest LTS version recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [ESLint](https://eslint.org/)

## Installation

Clone the repository and install dependencies:

```sh
npm install
```

## Available Scripts

### Development
```sh
npm run dev
```
Runs the application in development mode using `nodemon`. This automatically restarts the server on code changes.

### Build
```sh
npm run build
```
Compiles TypeScript files into JavaScript files.

### Start
```sh
npm run start
```
Runs the compiled JavaScript application using Node.js.

### Clean
```sh
npm run clean
```
Removes the build output directory to ensure a clean build.

### Lint
```sh
npm run lint
```
Checks the code for linting errors using ESLint.

### Fix Linting Issues
```sh
npm run fix
```
Attempts to automatically fix linting issues using ESLint.

## Project Structure
```
.
├── package.json # Project configuration and dependencies
├── tsconfig.json# TypeScript configuration
├── .eslintrc.js # ESLint configuration
└── README.md    # Project documentation
```

## Contributing
Feel free to submit issues and pull requests to improve the project!


