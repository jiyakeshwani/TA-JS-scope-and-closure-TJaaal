For the given code below:

- re-write the code in ways that system will understand

For Example:

1.

```js
var username = "Arya";
let brothers = ["John", "Ryan", "Bran"];

console.log(username, brothers[0]);

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello("Test");
```

<!-- Answer -->

```js
// Declaration Phase
var username = undefined;
let brothers;

function sayHello(name) {
  return `Hello ${name}`;
}

let message;
var nextMessage = undefined;

// Execution Phase

username = "Arya";
brothers = ["John", "Ryan", "Bran"];

console.log(username, brothers[0]);

message = sayHello(username);
nextMessage = sayHello("Test");
```

2.

```js
console.log(username, numbers);

var username = "Arya";
let number = 21;

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello("Test");
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
var username = undefined
let number =;

function sayHello(name) {
  return `Hello ${name}`;
}

let message =;
var nextMessage = undefined
// excecution phase
username = "arya"
number = 21

console.log(username, numbers);

message = sayHello(username);
nextMessage = sayHello('Test');
```

3.

```js
console.log(username, numbers);
let username = "Arya";
let number = 21;

let sayHello = function (name) {
  return `Hello ${name}`;
};

let message = sayHello(username);
var nextMessage = sayHello("Test");
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
let username =;
let number =;

let sayHello = function (name) {
  return `Hello ${name}`;
};;

let message =  ;
var nextMessage = undefined

// excecution phase
 username = 'arya';
  number =21;

 sayHello = `Hello ${name}`;

 message =  sayHello(username);
nextMessage = sayHello('Test');
```

4.

```js
let username = "Arya";
console.log(username, numbers);

let number = 21;
let message = sayHello(username);

let sayHello = function (name) {
  return `Hello ${name}`;
};

var nextMessage = sayHello("Test");
```

<!-- Answer -->

```js
// Your code goes here
```

5.

```js
console.log(name);
console.log(age);
var name = "Lydia";
let age = 21;
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase

var name = undefined
let age = ;

// excecution phase
name = "Lydia"
age = 21

console.log(name);
console.log(age);
```

6.

```js
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = "Lydia";
  let age = 21;
}

sayHi();
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
 function sayHi(name){
var name = undefined
let age=;
]
// excecution phase
function sayHi(name){
name = "Lydia"
age = 21

console.log(name);
console.log(age);}
```

7.

```js
sayHi();
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = "Lydia";
  let age = 21;
}
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
 function sayHi(name){
var name = undefined
let age=;
]
// excecution phase
function sayHi(name){
name = "Lydia"
age = 21

console.log(name);
console.log(age);}
sayHi();
```

8.

```js
sayHi();
let sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = "Lydia";
  let age = 21;
};
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
 let sayHi = function sayHi(name){
var name = undefined
let age=;
]
// excecution phase
sayHi = function sayHi(name){
name = "Lydia"
age = 21

console.log(name);
console.log(age);}
sayHi();
```

9.

```js
let num1 = 21;
console.log(sum);
var sum = num1 + num2;
let num2 = 30;
```

<!-- Answer -->

```js
// Your code goes here
// declaration Phase
let num1 = ;
var sum = undefined

let num2 = ;
// excecution phase

num1 = 21
sum = 21 + undefined
console.log(sum);
num2 = 30

```

10.

```js
var num1 = 21;

let sum2 = addAgain(num1, num2, 4, 5, 6);

let add = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
function addAgian(a, b) {
  return a + b;
}
let num2 = 200;

let sum = add(num1, num2, 4, 5, 6);
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
 var num1 = undefined
 let sum2 = ;
 let add = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
function addAgian(a, b) {
  return a + b;
}
let num2 =;
let sum =;

//excecution phase
num1 = 21
sum2 = addAgain(num1, num2, 4, 5, 6);
add = return a + b + c + d + e;
num2 =200
sum2 = add(num1, num2, 4, 5, 6);
```

11.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

let add = (a, b) => {
  return a + b;
};
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
function test(a) {
  let num1 = ;
  return add(a, num1);
}
let sum =;
let add = (a, b) => {
  return a + b;
};
//excecution phase
num1 = 21
sum = test(100);
add = return a +b
```

12.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

function add(a, b) {
  return a + b;
}
```

<!-- Answer -->

```js
// Your code goes here
// declaration phase
function test(a) {
  let num1 = ;
  return add(a, num1);
}
let sum =;
function add(a, b) {
  return a + b;
}
//excecution phase
num1 = 21
sum = test(100);

```
