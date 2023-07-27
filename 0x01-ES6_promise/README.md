# ES6 Promises

This repository contains a set of functions and tasks related to ES6 Promises in JavaScript. The tasks aim to cover various concepts, such as Promises, handling asynchronous operations, and using async/await. The functions are designed to be executed on NodeJS 12.11.x and tested using Jest.

## Learning Objectives

By completing this project, you will be able to explain the following concepts without the help of Google:

- Promises (how, why, and what)
- How to use the `then`, `resolve`, and `catch` methods
- How to use every method of the Promise object
- Error handling with `Throw / Try`
- The `await` operator
- How to use an `async` function

## Requirements

- Operating System: Ubuntu 18.04 LTS
- NodeJS version: 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A `README.md` file at the root of the project folder is mandatory
- Code files should use the `.js` extension
- Testing will be done using Jest and the command `npm run test`
- Code will be verified against ESLint rules
- All functions must be exported

## Setup

Follow the steps below to set up the environment for running the code and tests:

1. Install NodeJS 12.11.x in your home directory:

```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```

2. Verify the NodeJS and npm versions:

```bash
$ nodejs -v
v12.11.1
$ npm -v
6.11.3
```

3. Install Jest, Babel, and ESLint in your project directory:

```bash
npm install --save-dev jest
npm install --save-dev babel-jest @babel/core @babel/preset-env @babel/cli
npm install --save-dev eslint
```

## Function Details

The repository contains several functions and tasks, each addressing specific concepts related to ES6 Promises. Here's a brief overview of the functions:

1. `getResponseFromAPI`: A function that returns a Promise. Use it to understand Promise creation.

2. `getFullResponseFromAPI`: A function that returns a Promise with specific resolutions based on the provided argument (true or false).

3. `handleResponseFromAPI`: A function that appends handlers to a Promise, resolving or rejecting with specific attributes and logging a message to the console.

4. `handleProfileSignup`: A function that calls other functions returning Promises and collectively resolves them to log specific values to the console.

5. `signUpUser`: A function that returns a resolved Promise with specific attributes.

6. `uploadPhoto`: A function that returns a Promise rejecting with an error message.

7. `handleProfileSignup`: A function that accepts three arguments and calls two other functions returning Promises, resolving them collectively and returning an array with specific structures.

8. `loadBalancer`: A function that accepts two Promises and returns the value of the first resolved Promise.

9. `divideFunction`: A function that accepts two arguments and returns the result of the division or throws an error if the denominator is 0.

10. `guardrail`: A function that accepts a mathFunction (Function) and creates an array named queue, appending values or error messages based on the execution of the function.

## Testing

To test the functions, run the following command:

```bash
npm run test
```

Please ensure all functions pass the tests before considering the project complete.

Remember to create a `.babelrc` file to configure Babel properly and adjust any other necessary configurations for your development environment.

Feel free to explore and expand on the functions and tasks as you learn more about Promises and asynchronous JavaScript!
