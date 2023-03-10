# 🗒️ Class 04

## Reading Notes &mdash; Why this topic matters

The topics in the reading below matters because sets us up to create a better laid-out website or web/application and also begins to get the wheels churning on how to create sticky/fixed header & footers, and other stuff.

### Learning HTML

- To create a basic link, we wrap text or other content inside what element?
  - To create a basic link, we wrap a text or other content inside an `<a>` anchor element. For a link to actually bring you somewhere, we need to include the `href` attribute.

- The `href` attribute contains what information?
  - The `href` attribute contains the target location for the anchor element

- What are some ways we can ensure links on our pages are accessible to all readers?
  - Instead of using `click here` as the link, try to be more specific.
  - Keep link text as short as possible.
  - Minimize multiple copies of the same text
  - Don't use URLs as the link text.

### CSS Layouts

- What is meant by “normal flow”?
  - Normal flow is the natural way a webpage lays out all the elements by default.

- What are a few differences between block-level and inline elements?
  - Block-level Elements sit on their own line by themselves. When we add multiple block level elements after another, they will stack one below another by default.
  - Inline elements sit next to each on the same line by default. If at anypoint the elements/content cannot fit on the line, it would just overflow into the next line.

- `___` positioning is the default for every html element.
  - Every element is position `static` by default.

  > lecture notes: `relative` positioning is positioned relative to the parent element or siblings but will not ever be outside the parent.
  > `sticky` positioning is a combination of fixed and relative positioning

- Name a few advantages to using absolute positioning on an element.
  - Using the `position: absolute` styling is useful for when we want certain elements to stay on the page and not interfere with the content and other elements on the page. For example, newsletter signup modals and back to top buttons.

- What is a key difference between fixed positioning and absolute positioning?
  - Fixed positioning fixes an element based on where its placed on the visible portion of a viewport where as absolute fixes itself to the nearest positioned ancestor element/tag.

### Learning JS

- Describe the difference between a function declaration and a function invocation
  - When we declare a function, we are creating a function that we can add parameters and call on later one when we need to run the code wrapped in the function.

  - When we call a function, we are telling the computer that we need to execute the block of code.  
  
    - Invokes can happen multiple ways
      - when an event happens (onload, onclick, etc)
      - when called in another javascript code
      - and automatically

- What is the difference between a parameter and an argument?
  - There are essentially the smae thing. According to the MDN Docs, the word parameter is exchangable with with arguments, properties, or sometimes even attributes. example `function(name)` vs `function('donna')`;

  > return statement: passing a value of a thing we want something out of a function.

### 2 Benefits of Pair Programming

- Learning from fellow students - you get a different view of how someone would attempt a block of code and see how maybe that would be more efficent than what you are doing.
- Social Skills - Pair programming is great for improving social skills because you learn ways to expain your code in a way that makes sense to the other programming.

## Things I want to know more about

- Adding parameters to the functions declared in app.js
- if we only specify one parameter in the function, could we try and futher down the in the function?

## Lecture Notes
