# 🗒️ Class 26

## Readings

### React Quick Start

- What are the building blocks of a React app?
  > Components are the building blocks of react

- What is the difference between an HTML element and a React component?
  > React components use JSX.

- What is JSX and why do we use it?
  > JSX is Javascript syntax. While it is optional, most React projects use it for its convenience.

- Describe the process of embedding JavaScript expressions in JSX.
  > Javascript Expressions can be embedded in JSX by using `{}` curly brackets

- Does React or JSX have any special features for iteration or conditional logic?
  > You can use traditional `if-else` statements, `conditional ? operators`, `for loops`, and `array.map()` functions

- How does React know to respond to a user’s inputs?
  > react knows to respond to user input using states and events.

- What word indicates that a React component manages data with a Hook?
  > A function that starts with `use` indicates that data is managed with a hook.

- How can two react components share data?
  > This can be done by moving state "upwards" to the closest component that contains all the things the need to use the data. 

### Render and Commit

- What are the three steps of refreshing a React UI?
  > Trigger a render, render the components, commit changes to the DOM.

- How do you trigger updates to a component after the initial render?
  > If a component has been rendered, you must use the `set` function to update the state in order to trigger any further rendering.

- Does React recreate DOM nodes on every rerender?
  > React will only recreate the DOM nodes if it sees a difference between the renders.

- After React has updated the DOM, what still needs to happen before the user sees the change?
  > After the DOM has been updated by the DOM, the browser sill need to go through the process of "browser rendering" to make the changes visible. 
