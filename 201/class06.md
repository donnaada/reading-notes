# 🗒️ Class 06: Problem Domain, Objects, and the DOM

This reading material is important because we start to learn about manipulating the DOM and outputting object name/value pairs onto an HTML using JavaScript.

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
    > We use dot notation to speifcy the item we want to access within an object. We use bracket notation to access to a property within a property.

1. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?
    > `this` refers to the current object the code is being written in.Example This referes to the dog Object

[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

1. What is the DOM?
    > DOM stands for Document Object Model - The DOM represents the html page that we can change the document structure, style, and content.
1. Briefly describe the relationship between the DOM and JavaScript.
    > We can use JavaScript to access and manipulate the DOM but the DOM can be built for any language.

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

## Reading Notes

Object literal - object created with curly brackets

- It is a data structure like an array but instead of indices, objects use keys (key/value pairs)

``` javascript

// array
let pokemon =["pikachu"];
pokemon[0] //returns pikachu

//object
let pokemon ={
  name: "pikachu"
}
pokemon.name; //still returns pikachu
```

When to use array vs object:

- When all the things are the same type we can use array
  - > `let pokedex = ["pikachu", "charmander", "bulbasaur"];`
- If we want to add more information we can use object
  - > `let pokemon = {name:"pikachu", type:"electric"};`

- contextual this
  - > this is a keyword that changes depending on where in our code we are calling it
    - > refers to the object surrounding the "this" keyword

- brackets vs dot notation
  - two ways to refer to properties
    - `object.property` - Dot notation uses the name of a property attached to the object, prepending by an a
    - `object["property"]`- uses square brackets and reads from a string value; allows us to use variables; helpful when we want to read from a property that has a variable

- Function on object are known as methods

### DOM

DOM is the virtual representation of the HTML Documentation.

- document.selector.textContent is used if we are just changing text.

``` javascript
let parentElement = document.getElementById('parentID')
let childElement = document.createElement('tagType');

childElement.textContent = object.property;

parentElement.appendChild(childElement);

//adds style
element.style="inline styles"
```

