# 🗒️ Class 02: Basics of HTML, CSS & JS

The reading for class 02 contine to touch on using semantic elements in our HTML. It touches on using `<abbr>` which I have never thought about doing in the past. It also goes over the multiple ways to add styling to a page. From the reading, we know that CSS can be added 3 ways, but i wanted to include that we could also add styling to a page using javascript, Im not too sure how yet but I have seen it done :)!

## Reading

### Introduction to HTML

1. Why is it important to use semantic elements in our HTML?  
It is important to use semantic elements because we want to make sure that our site is accessible to those who have a vision imparement.

2. How many levels of headings are there in HTML?  
There are 6 levels of heading `<h1> to <h6>`

3. What are some uses for the `<sup>` and `<sub>` elements?  
superscript and subscript are used when we want to write out days of the date (1st, 2nd, etc) and for science and math equations and/ot formulas.

4. When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?  
When using the abbreviation element, we must always include a title attribute with the full word as the value.

### Learn CSS

1. What are ways we can apply CSS to our HTML?  
We can apply css to our html using external stylesheets, internal styles wrapped in the style tag, inline styling, and also with Javascript.

2. Why should we avoid using inline styles?  
Using inline style vs using a class (especially if we are using the same elements in muliple locations) make it hard to handle updates to a website because if we make a change to one line, we would have to find all the other places we use the same block of code and make/add inline styling in those locations too.

Review the block of code below and answer the following questions:

- What is representing the selector?  
  - The Selector is `h2`
- Which components are the CSS declarations?  
  - The declarations are the property &amp; value pairs ie `color:black;` and `padding:5px;`
- Which components are considered properties?
  - The properties are the text to the left of fo the colon ie `color` and `padding`.

``` css
   h2 {
     color: black;
     padding: 5px;
   }
```

### Learn JS

- What data type is a sequence of text enclosed in single quote marks?  
  - String type

- List 4 types of JavaScript operators.
  - addition (`+`)
  - assignment (`=`)
  - NOT equal to (`!=`)
  - Strict equal (`===`)

- Describe a real world Problem you could solve with a Function.
  - Find the sum of two number
  
  ``` javascript
  function sum(x,y){
    let sum = x + y;
    return sum;
  }
  ```

- Making Decisions In Your Code – Conditionals.

- An if statement checks a __ and if it evaluates to ___, then the code block will execute.
  - Condition; true.

- What is the use of an else if?
  - We use else if if there are additional conditions we want to evaluate

- List 3 different types of comparison operators.
  - `<`, `<=`, `===`

- What is the difference between the logical operator && and ||?
  - `&&` check to see if all the expressions evaluate true.
  - `||` check to see if on of the listed expressions evaluate true.

## This I Want to know

- Do we use `<abbr>` every single time we have an abbreviation on the page or just the first time?
