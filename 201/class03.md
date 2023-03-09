# 🗒️ Class 03 HTML Lists, Control Flow with JS, and the CSS Box Model

## Reading Notes

### Learning HTML

- When should you use an unordered list in your HTML document?  
  - We should use an unordered list when the collection of items do not have to be in a specific order.

- How do you change the bullet style of unordered list items?
  - You can change the bullet syle by using the `list-style-type` property.

- When should you use an ordered list vs an unorder list in your HTML document?
  - Deciding whether to use an ordered list versus an unordered list all comes down to the type of content you are outputting. If the list needs to be in a specific order, use an `ol` otherwise use `ul`.

- Describe two ways you can change the numbers on list items provided by an ordered list?
  - There are two ways to change the numbers on a list item for ordered lists
    - To change the numbering to go from the largest number to the smallest, you could use the `reversed` attribute.
    - If you want to change what number the list starts at, you would use the `start` attribute followed by the number you would like the list to begin.
    - \* Note: to change the numbering type, you you would modify the `type` attribute to
      - `a` - lowercase letters
      - `A` - uppercase letters
      - `i` - lowercase Roman numerals
      - `I` - uppercase Roman numerals
      - `1` - numbers (default)

### Learning CSS

- Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
  - In the story "The Box Model", Padding is one of the main characters who is part of the "inner circle" and is a ray of sunshine because she is not able to have any negative values. Meanwhile, margin is on the outside of the "inner circle" and while she is usually positive, she has her moments when she is negative.

- List and describe the four parts of an HTML elements box as referred to by the box model.
  - Content - The part of the box where the content is displayed
  - Padding - The space between the content and the border of the box
  - Border box - Its the outline of the box model that wraps the content and padding.
  - Margin - The outside layer that wraps the content, padding and border.

### Learning JS

- What data types can you store inside of an Array?
  - Arrays can store strings, numbers, arrays and objects.

- Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
  - Yes, the people array is valid JavaScript. In order to access the values stored in the people array, you have to type the array name, the square brackets, and then the object number starting at 0.

``` javascript
  For example,  
  concole.log(person[1]) // Arrays start with 0 then counts up.
```

``` javascript
 const people = [
  ['pete', 32, 'librarian', null], 
  ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], 
  ['bill', null, 'artist', null]
  ];
 ```

- List five shorthand operators for assignment in javascript and describe what they do.
  - `x += 3` is the equivalent of `x = x + 3`
  - `x -= 4` is the equivalent of `x = x - 4`
  - `x *= 5` is the equivalent of `x = x * 5`
  - `x %= 6` is the equivalent of `x = x % 6`
  - `x /= 7` is the equivalent of `x = x / 7`

- Read the code below and evaluate the last expression and explain what the result would be and why.
  - The last expression in the code below will evaluate to the the string `'10dog'`
    - `a` evaluates to the number 10
    - `b` evaluates to the string 'dog'
    - `c` evaluates to the false
    - `a + c` evaluates to `10 false` or `10`
    - `b` then evaluates to the concatenation of a `('10')` and b `('dog')`

``` javascript

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
 ```

- Describe a real world example of when a conditional statement should be used in a JavaScript program.
  
  - One example of when a conditional statement should be used in a JavaScript program is when we are trying to get input by the website visitor.

- Give an example of when a Loop is useful in JavaScript.
  - A loop is useful when we are trying to cycle through a list of things and also

## Lecture Notes

### arrays

let people = ['p1'] // array name is people
people.length // displays length

#### Adding to Array

people.push('p2') // adds to the end array
people.unshift('p3') // adds to beginning of array

#### Removing from Array

people.pop() // drops the last item in an array
people.shift() // drops the first item in an array

### loops

#### for

for (initialize; condition; increment){
  //code to execute
}

#### while

initialize somewhere above loop

while (condition){
  // code to execute
  // increment/break
}

#### do while

will run at least once

do {
  // code to run
} while (condition)

### Things i want to learn

- \* This part will be added as we go through the lectures or any other question comes up.
