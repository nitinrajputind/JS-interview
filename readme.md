## Q2. What are the differences between var, let and const?

### var - 
    1. Redeclare and reinitilized
    2. Global scope and Function Scope
    3. Hoisting
    4. Used before introduce ES6
### let
    1. not Redeclare and reinitilized
    2. no Hoisting
    3. Block scope, Global Scope
    4. TDZ
    5. introduce in ES6
### const
    1. not Redeclare and Not reinitilized 
    2. no Hoisting
    3. Block scope, Global Scope
    4. TDZ
    5. introduce in ES6

## Type of Scope
1. Global Scope
2. Function Scope
3. Block Scope

## Q3. Hoisting - Hoisting is the js mechanism where var and function declaration are moved to top of their scope before code execution.
    1. function Hoisting
    2. var keyword Hoisting
## Q4. What is a Temporal Dead Zone (TDZ)?
    - when trying to acceess a variable before it's decleration with let and const keyword.
    - introduce to imporve the code quality by detecting & preventing to use variable.
## Q5. What is meant by first class functions?
    - Assign a function to a variable is first class function.
## Q6 . Pure Function - A pure function in JavaScript is a function that returns the same result if the same arguments(input) are passed in the function.
---
## Q7. Execution Context

    - This is for Synchronous JavaScript
    1. Global Execution Context
    2. Function Execution context
    3. Memory Allocation
    4. Code Execution 
    5. Call Stack
   
    - Asynchronous JavaScript
    1. Event Loop
    2. Callback queue
    3. Microtask Queue
    4. Call Stack

---
# 19th June

## Chrome - V8 Engine
## Safari - JavaScriptCore (Nitro)
## Firefox - Spider Monkey

## What is the spread operator?
    - Spread operator allows us to destructure the non-primitive datatype like object and array to access elemnets individually.
    - The spread operator is a feature in JavaScript that allows an iterable (such as an array or a string) to be expanded into individual elements. The spread operator is denoted by three dots (...).
    - The JavaScript spread operator ( ... ) allows us to quickly copy all or part of an existing array or object into another array or object.

## What is use of setTimeout?
    - it is used to delay the output with given time.
    - The setTimeout() method sets a timer which executes a function or specified piece of code once the timer expires.
## What is setInterval?
    - They are going to excute the code after given time peroid.
  
## What are callbacks?
    - A function that can pass inside another function as an argument.
    - A callback is a function that passed as an argument to another function.
## Callback Hell
    - Callback Hell is essentially nested callbacks stacked below one another forming a pyramid structure.

## Difference between undefined vs not defined vs NaN?
1. undefine - variable dec. but not init.
2. not define - variable is not declear.
3. NaN - Not a Number