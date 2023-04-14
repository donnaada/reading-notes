# 🗒️ Class 05: Putting it all together

## [React Docs - Thinking in React(https://reactjs.org/docs/thinking-in-react.html)]

-What is the single responsibility principle and how does it apply to components?
    > The SRP is a principal that states that every module/function should have ONLY ONE role, with components, this is the same. Each component should do only one thing. Once it starts doing multiple things, we should consider splitting it into two serparate components.

-What does it mean to build a ‘static’ version of your application?
    > Building a static version of our application means creating an application that brings in all the components through props but not yet with interactivity.

-Once you have a static application, what do you need to add?
    > After you have a static application, you need to  identify the apps minimal state data.

-What are the three questions you can ask to determine if something is state?
    > That it remain unchanged over a period of time? Is it passed in from a parent component? Can we compute it?

-How can you identify where state needs to live?
    > Identify all the components that rely on a specific state, Find their closest common parent component, and then from there you can decide if you want it in that common parent, a component above the common parent or if you want to create a new component purely to hold the state.


## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

-What is a “higher-order function”?
    > A higher Order function is a function that operates on other functions and either takes those functions in as arguments or by returning a fu ncction.

-Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
    > On line 2 of the greaterThank function, we are returning a new function that evaluates into a `True` or `False`

-Explain how either map or reduce operates, with regards to higher-order functions.
    > The map() function transforms an array and returns a new array. The new arrays will always start off being the same length but the content should be different. The reduce() is used to reduce an array to a single value by applying a function and adding onto a result value
