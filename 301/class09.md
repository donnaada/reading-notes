# 🗒️ Class 09 Functional Programming

- What is functional programming?
    > A style of programming that emphasizes the use of functions and avoids changing-state and mutable data.

- What is a pure function and how do we know if something is a pure function?
    > A pure function is  a function that adheres to the strict deifintions of purity. A pur function must return the same result if give the same argument and caannot cause any observable side effects.

- What are the benefits of a pure function?
    > Pure functions are easier to test.

- What is immutability?
    > Immutability means cannot be change or cant be changed over time. 

- What is Referential transparency?
    > Referential transparency occurs when a function consistently yeilds the same results for the same input. `pure functions + immutable data = referential transparency`

# Videos

- What is a module?
    > A self-contained block of code that has a certain functionality that can be called on when needed anywhere during the code.
- What does the word ‘require’ do?
    > Its used to load specify what module we want to bring into our working file and from what path the module is located at.

- How do we bring another module into the file the we are working in?
    > By using `var <variable> = require('./path to file/filename')`

- What do we have to do to make a module available?
    > Explicityly say what part of the module we want to make available outside by using `module.exports = <module name>;`