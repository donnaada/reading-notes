# 🗒️ Class 09 Forms and JS Events

## HTML Forms

- Why are forms so important in web development?
  - A form is a point of interaction between a user and a website.

- When designing a form, what are some key things to keep in mind when it comes to user experience?
  - When designing a form, we have to think about how we want our form to look and to think about what information we want the user to enter.

- List 5 form elements and explain their importance.
  - `<form>` - defines the form
  - `<label>` - is the description/caption for a form input element
  - `textarea` - an multiline input field.
  - `<input>` - a field that a accepts inputs from the user
  - `<button>` - gives the users the ability to sumbit or send the data entered on the form

## Learn Js

- How would you describe events to a non-technical friend?
  - An event are things that happened to the browser while programming ie `onload()` and  `onclick`

- When using the addEventListener() method, what 2 arguments will you need to provide?
  - what the event needs to listen for, and a function that runs when that event happens

- Describe the event object. Why is the target within the event object useful?
  - a parameter inside an event handler

- What is the difference between event bubbling and event capturing?
  - Event bubbles target the innermost child element then goes back out to the parent (most nested to least) and event capturing does the opposite.
  
## lecture notes

API - Application Programming Interface

DOM = API For HTML elements in JS

inputElement.addEventListener('input', function())

``` javascript
// find what element we want to add action/ event to
let inputElement = document.getElementById('inputElement');
let formElement = document.getElementById('formElement');

// event/action
function functionName{
  console.log('im a function');
}

// attach event to element
inputElement.addEventListener('input', functionName)

// browser has some defaults, prevent default submissino behavior so page doesnt reload
formElement.addEventListener('submit', function(event){
  event.preventDefault(); //dont refresh page
});
