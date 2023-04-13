# 🗒️ Class 04: React and Forms

## React Docs - Forms

- What is a ‘Controlled Component’?
  > A controlled component is an input form element whose value is controlled by React

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  > We should update state as soon as a user enters the information so that if they leave the page and come back or have a drop in connection, they could always get back to where they were at on the form.

- How do we target what the user is entering if we have an event handler on an input field?
  > The value of the input field

## The Conditional (Ternary) Operator Explained

- Why would we use a ternary operator?
  > Personal Preferences but some of the reasons I've heard include the ability to create less lines of code and for other it was beause it was easier to understand what the code does.

  - Rewrite the following statement using a ternary statement:

    ``` javascript
    //Original code
      //if(x===y){
        //console.log(true);
      //} else {
       // console.log(false);
      // }

      let boolean = (x === y ? true : false);
      console.log(boolean);
    ```
