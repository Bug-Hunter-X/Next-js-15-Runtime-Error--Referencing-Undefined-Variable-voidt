# Next.js 15 Runtime Error: Referencing Undefined Variable

This repository demonstrates a common runtime error in Next.js 15 applications where referencing an undefined variable leads to unexpected behavior. The error is not caught during development, highlighting the need for robust error handling.

## Bug Description
The `About` page in this example attempts to access a variable (`nonExistentVariable`) that is not defined within its scope. This causes a runtime error in the browser.

## Solution
The solution involves proper error handling or ensuring that variables are defined before being accessed.  In this case, adding a check for the variable's existence prevents the error. 

## How to reproduce
1. Clone this repository.
2. Navigate to the project directory using your terminal.
3. Run `npm install` to install the dependencies.
4. Run `npm run dev` to start the development server.
5. Navigate to `/about` in your browser. You'll observe the runtime error.

## How to fix
Refer to the `aboutSolution.js` file for the corrected code.