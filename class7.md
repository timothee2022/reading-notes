Class 7

# My Reading Notes for Class7

## Read: 07 - Programming with JavaScript

### 1. Control flow
The control flow is the order in which the computer executes statements in a script. For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in.

if (field==empty) {
    promptUser();
} else {
    submitForm();
}

### 2. JavaScript Functions
A JavaScript function is a block of code designed to perform a particular task. A JavaScript function is executed when "something" invokes it (calls it).

Example
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}

### 3. JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Example:
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

### 4. Function Return
When JavaScript reaches a return statement, the function will stop executing.

Example:
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

### 5. Functions Used as Variable Values
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

let x = toCelsius(77);
let text = "The temperature is " + x + " Celsius";

Here is the link to my website: https://github.com/timothee2022