1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
function declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

function expression

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

function expression

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

function expression
arrow function

```js
let percentage = (marks, total) => (marks * 100) / total;
```

function expression
arrow function 3. Why is a function definition an expression in JavaScript? Give one example of function expression.
A function defination is an expression in javascript because it stores a series of steps that we take to perform an action
example of function defination:

```js
let fullName = function (firstName, lastName) {
  return `${firstName} ${lastName}`;
};
```

4. Why is a function call an expression in JavaScript?
   A function Call is an expression in javascript because it is always followed by parenthesis
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // invalid because function call is an expression and we can not store an expression in a variable
five = add; // invalid because add is not a function call
five = five(10, 11); // invalid
five = function () {
  return "Hello";
}; // valid because it is a function expression
```

6. What is the difference between function definition and function call? Explain with an example.
   function defination is a way to store a series of steps that we take to perform an action and function call is way to excecute that series of steps that we stored in function defination.
   example:

```js
function defination
function percentage(marks, total) {
  return (marks * 100) / total;
}
function call
percentage(40 , 100);
```

7. What is the similarities between function definition and function call?
   both of them contain the name of the function
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; //  invalid because user is not defined
```

9. What is higher order function explain with an example.
   higher order functions are functions which take a callback function as an parameter and also can return a function
   example:

```js
let sum = numbers.reduce((accumulator, currentValue) => {
  return accumulator + currentValue;
});
```

10. Explain what is callback function. Why you can pass a function inside a function
    A callback function is a function which can be passed inside a higher order function.
