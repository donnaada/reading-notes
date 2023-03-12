# 🗒️ Class 06: Problem Domain, Objects, and the DOM

This reading material is important because

## Reading

[Javascript Objects Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1. How would you describe an object to a non-technical friend you grew up with?
What are some advantages to creating object literals?
    > You can thing of an object like a team roster. Its a list of similar things. example  

    ``` json
      const roster = {
        playerName: 'John Doe',
        position: ''
      }
    ```

1. How do objects differ from arrays?
    > With objects, we can call on items within the object using the name which is from the name/value pair vs arrays where you would call on a specific position.

1. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
    >

1. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

## Other Notes

- Object methods are functions that allow the object to do something with its data. Here is an example from [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics).

``` js
  const person = {
  name: ["Bob", "Smith"],
  age: 32,
  bio() {
    console.log(\`${this.name[0]} ${this.name[1]} is ${this.age} years old.\`);
    },
    introduceSelf() {
    console.log(\`Hi! I'm ${this.name[0]}.\`);
    },
  };

```
