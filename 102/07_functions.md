# 🗒️ Class 07: Programming with Javascript

## What is control flow?

Control flow is the flow in which a computer would execute a statment.

## What is a JavaScript function?

A Function is a block of code used to perform a specific task.

* Function codes can be reused, multiple times.
* One code can be used with different arguments to get different results

```javascript
let newFunction = function(){
  console.log("im in a function")
}

newFunction();
```

## What does it mean to invoke - or call - a function?

When we call a function, we are telling the computer that we need to execute the block of code.

Invokes can happen multiple ways

* when an event happens (onload, onclick, etc)
* when called in another javascript code
* and automatically

---

the ()operation calls the function

* myFunction() is a function
* myFunction is an object

functions can be used as variable values. This means we dont have to declare a variable with the result of the function, we can just call on it directly.

``` javascript
let myName = getName(Donna);
let text = "Hi my name is " + myName + " :)";

//Instead we can use
let text = "Hi my name is " + getName(Donna) + " :)";

```

## What are the parenthesis () for when you define a function?

The parenthesis is used include parameters. We can have single parameters or multiple parameters. If we are using multiple parameters, it must be separated by commas.

## Other Reading notes

### returning a value

we only add return if we want something out of a function.

### functions

can invoke function before declaration but cannot invoke a function expression until after

### local variables

A local variable is declared inside a function and can only be access in a function.

### Objects

#### Evaluate to object example [mdn web docs_](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

``` javascript
const obj = {};

obj.x = 3;
console.log(obj.x); // Prints 3.
console.log(obj); // Prints { x: 3 }.

const key = "y";
obj[key] = 5;
console.log(obj[key]); // Prints 5.
console.log(obj); // Prints { x: 3, y: 5 }.
```

read [working with objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

#### Destructing Objects

Extracting data from arrays or objects using sytax that mirrors the construct of the array or object literals

``` javascript
const foo = ["one", "two", "three"];

// without destructuring
const one = foo[0];
const two = foo[1];
const three = foo[2];

// with destructuring
const [one, two, three] = foo;
```

## Refactor
