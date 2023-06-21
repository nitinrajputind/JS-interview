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

---
# Day 3 - 20th June 2023

## What are promises and why do we need them?
    - Promise are use to handle async operation in JS. easy to handle callback hell, also use to handle the error.
    - basically in promise there are Three stage
        1. Pending
        2. Resolve - (then method)
        3. reject - (catch mentod)
    - initial stage of any promise is always pending.

## Q - We have three promise, and we want to combine all then and catch method by using Promise.all.

## What is promise chaining?
    - its a technique to chain multiple asynchronous operation together using promises.
    - Promise chaining is a technique in JavaScript to execute multiple asynchronous operations in a specific order by chaining promises together using the then method
    - Multiple .then method.
  
## DOM - Document Object Model
    - Document object model. basically it is javascript mechanism by which we can change the document structure, style, and content.
    - DOM is the data representation of the objects that comprise the structure and content of a document on the web.
    - Different method in DOM
      - Id - getElementById - return unique value
      - querySelector -       return unique value    
      - Class - getElementsByClassName 
      - tag Name - getElementsByTagName
      - querySelectorAll 

    - addEventListener - (event, callback function)

## Closure - 
    - A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment).
    - Closure is the combination of two function (min).
    - inner function is able to excess the outer function variable but vise-varsa not possible.
    - outer func and inner func is going to create a Lixical environment.

## How many operators do we have in JS ?
    1. Arithemic operator
       1. Add, Sub, Multi, Div(/), Module (%), Expontial (**), increment ++, decrement--
    2. Assignment Operator
       1. Assign (=), Add Assign (+=), Sub Assign (-=), (*=), (/=), (%=)
    3. Bitwise Operator
       1. Bitwise OR (|), Bitwise AND (&), Bitwise NOT (~), Left shift (<<), right shift(>>)
    4. Comparision Operator
       1. equal (==), strict equal (===), Not equal (!=), Strict Not equal (!==), greate than, less than, greate than equal, less than equal
    5. Logical Operator
       1. AND (&&)
       2. OR (||)
       3. Not (!)
    6. Ternary Operator
       1. (Condition) ? "Execute True Condition" : "Execute False Condition"
    7. typeof Operator
       1. return datatype

## What are objects in javascript?
    - Non-premitive data type
    - store date in the form of Key-Value pair saparated by colon.
    - Key - Properties : Value 

# Day 4 - 21st June 2023 

## Function Constructor - 
    - A function constructor is a way to create a object using a function as a blue print or template.
    - it allow you to define a reusable structure for creating multiple object with similar properties and method.

## Call, Apply and Bind - 
    - These all three methods are used to invoke a function where we are supposed to pass an object as first argument and at the time of definition we don't have mention this object as a parameter and we can access the values of object by using this keyword in function definition.
    - Call : The call method is used to invoked a function with a specific 'this' value, and arguments provide individuly.
    - The call() method invokes a function in which first argument will be the object and rest of the arguments required by function will be provided as an individual arguments.
    - Apply : Apply is similar with call, but take argument as an array.
    -  The apply() method invokes a function in which first argument will be the object and rest of the arguments will be passed as an array of elements.
    - Bind - Bind is a function that helps you create another function that you can execute later with the new context of this that is provided.
    - The bind() method returns a new function and this function will be having the reference of the object passed, now whenever you want to use this returned function in the code you can use it by passing rest of the arguments.

## Async/Await - 
    - An async function is a function declared with the async keyword, and the await keyword is permitted within it. The async and await keywords enable asynchronous, promise-based behavior to be written in a cleaner style, avoiding the need promise chains.


## Inheritance:
    - Inheritance is a fundamental concept in object-oriented programming that allows objects to inherit properties and methods from other objects. It enables code reuse, promotes modularity, and facilitates the creation of hierarchical relationships between objects.
    - In JavaScript, inheritance is typically achieved through prototype-based inheritance. Objects in JavaScript can have a prototype, which is another object from which they inherit properties and methods.

## Prototype:
    - The prototype is an object that is associated with every JavaScript object. It serves as a blueprint or template for creating new objects through inheritance. The prototype object contains properties and methods that are shared among all instances created from it.
    - 