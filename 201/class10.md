# 🗒️ Class 10: Debugging

## What went wrong with JavaScript

- Name some key differences between a Syntax Error and  Logic Error.
  - Syntax errors are spelling errors in code that stop the program from continuing to run. Logical errors are errors with the code not doing what was intended or producing incorrect results.

- List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
  - Some example of a few errors that I encountered include
    - Event not running and spitting out an error because I typed `evend` instead of `event`.
    - Infinite loop because of the wrong comparison operator used.
    - A part of the output not showing becuase i forgot to invoke a function.
    - Failing to define a variable

- How will this topic continue to influence your long term goals?
  - This topic will make me more aware of the other errors out there and has also made me want to look more into debuggers.
  
## The JavaScript Debugger

- How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
  - a debugger is to code, as a exterminator is to pests. If you have a bug at home, most of the time you dont find it.

- Define what a breakpoint is.
  - A breakpoint In the place in the code that we want it to stop running and see whatexactly doing and hopefully get one close to fixing our code.

- What is the call stack?

  - a Function we acall in other functions();

## Lecture Notes

### Errors

#### Types

- Syntax errors - Errors caused by typos, missing closing brackets, wrong characters etc that javascript cant computer
- Reference error - Errors caused by trying to refer to something that doesnt exist. return values are not as expected.
- Type error - Ofter seen with objects. Data type is not what is expected
- Range error - Numerical Issue (creating an array with negative space)

#### Pillars of Debugging

- Read your Error Messages
- use console.log to audit and not trace
  - only leave informative console.logs
  - give message about why and what is being logged
- use debugger statment to trace code
  - autit value not as expected, try and use debugger.
