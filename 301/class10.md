# 🗒️ Class 10 In memory storage

## Understanding the JavaScript Call Stack

- What is a ‘call’?
  > A call is a function invocation
- How many ‘calls’ can happen at once?
  > CAlls are done one and a time
- What does LIFO mean?
  >`LIFO` means Last In, First out
- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

  ```javascript
  const hello = () => 'hello!'; 
  const myName = (name) => hello() + `My name is ${name}`; 

  myName('Donna'); 

  // myName('Donna') added to the call stack with Donna parament/argument
  // myName adds hello() function to call stack
  // hello() returns 'hello!' and is removed from stack
  // myname returns 'hello! My name is Donna' and is removed from call stack
  ```

- What causes a Stack Overflow?
  > Stack overflow occurs when a functions calls on itself without an exit point.

## JavaScript error messages

- What is a ‘reference error’?
  > Occurs when we are trying to reference something that has not been defined.

- What is a ‘syntax error’?
  > Syntax errors happen when somethat cannot be parsed in terms of syntax.

- What is a ‘range error’?
  > This occurs when we try to manipulate an object with somekind of length and we give it an invalid length

- What is a ‘type error’?
  > This error occurs when we try to use or access things that are incompatible.

- What is a breakpoint?
  > A breakpoint is something we can add to our code to tell the program that we want to sopt at a certain point in the code.

- What does the word ‘debugger’ do in your code?
  > Tell signifies where in our code we want to stop at to debug.
