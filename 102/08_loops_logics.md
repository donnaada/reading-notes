# 🗒️ Class 08: Operators and Loops

## What is an expression in JavaScript?

An expression in javascript is a unit of code that resolves to a value.

```Javascript
// This is an example of an expression that have a side effect ie assignment of value
  x = 'I am a string'; // We have assigned 'x' a string value of 'I am a string'

// The second example of expression are codes that are done to evaluate something.
  a = 3 === '3' // This expression uses the strict equal (===) operator to compare the two variables and return a boolean of true or false; this example stores the value false in the variable a.
```

## Why would we use a loop in our code?

Loops are used to do something repeatedly.

## When does a for loop stop executing?

A for-loop stops executing once the value of the condition is false. if a condition is not included, the for loop runs forever.

``` javascript
// for (initilization; condition; afterthought){
  for (let i = 0; i < 5; i++){
  // statement
  console.log(i);
}
```

## How many times will a while loop execute?

A while loop will continue to execute WHILE the condition is true
