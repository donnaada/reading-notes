# 🗒️ Prep: Data Structures and Algorithms

## Discussion Questions

1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
    - Big-O. Its the measure of long it takes to run an algorithm and/or how much memory is used by that algorithm.

1. How can we ensure that we’ll avoid an infinite recursive call stack?
    - Because Recursive functions calls on itself, its easy to end up with an infinite loop if we write our function incorrectly. To ensure we avoid an infinite call stack is to make sure we include a base case which tells the function not to call on itself anymore.