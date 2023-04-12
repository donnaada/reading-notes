# 🗒️ Class 03: Passing Functions as Props

## [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

- What does .map() return?
  > If there are no other functions or expressions called when using the map function, what returns is a new array with values mapped to the original array.

- If I want to loop through an array and display each value in JSX, how do I do that in React?
  > If we want to loop through an array and display the value in react, we could embed it in a return in between curly brackets with an inline map() function.

- Each list item needs a unique ____.
  > Each item needs a unique key

- What is the purpose of a key?
  > The purpose of a key is to help react identify changes to an item (add, update, remove, etc.)

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- What is the spread operator?
  > The spread operator `...` is a syntax used to add items to an array, combine array, objects, and to spread an array out into funtion arguments.

- List 4 things that the spread operator can do.
  > Add items to an array, combine arrays, combine objects, and spread an array into function arguments.

- Give an example of using the spread operator to combine two arrays.

  ```javascript
  let array1 = [1, 2, 3];
  let array2 = [3,4,5];
  let combinedArray = ...[...array1,...array2];
  // **OR** //
  let combinedArray2 = [...array1,...array2];
  ```

- Give an example of using the spread operator to add a new item to an array.

  ```javascript
  let originalArray = [0]
  let array1 = [1, 2, 3];
  let addedArray = [originalArray, ...array1];
  ```

- Give an example of using the spread operator to combine two objects into one.

  ```javascript
  let object1 = {one: 1};
  let object2 = {two:2};
  let copiedArray = {...object1, ...object2};
  ```

## [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

- In the video, what is the first step that the developer does to pass functions between components?
  > Figure out what state we are trying ot change and Create the function whereever that is.

- In your own words, what does the increment function do?
  > Passes in a specific person's name, find the matching name in the array/object and update that specific one.

- How can you pass a method from a parent component into a child component?
  > By passing it in as a props from the parent component to a child component.

- How does the child component invoke a method that was passed to it from a parent component?
  > by using the `this.props.methodName()`
