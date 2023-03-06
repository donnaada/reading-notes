# 🗒️ Class 01 : Setup Developer Toolbelt

The topics covered in the Class 01 Reading go over the basics of HTML, CSS, and JavaScript. It covers how data is transmitted between computers, how a browser reads the different markup and programming languages, and also semantic vs syntax style coding.

## Getting Started

- Compose a short poem describing how HTTP sends data between computers.  

> HTTP is how we send  
> Data between computers, devices, and friends,  
> First, we get the IP address of the site's (home) server,  
> The we use TCP/IP as a way to head over,  
> If the server approves, and send the client a "200 ok",  
> All the data packets get sent, and they can view that site all day :)  

- Describe how HTML, CSS, and JS files are “parsed” in the browser.  
The browser first Parses the HTML Document. It knows its an HTML document because we declare it at the top of the page using `<!DOCTYPE html>`. After it 'parses' the HTML, it a request back to the Server looking for any external css files in a `<link>` element and JavaScript files or codes found in a `<script>` element. Once it gets those back, it continues to parse the CSS and JavaScript files.

- How can you find images to add to a Website?  
There are multiple ways to find images to add to a website. One way is to use google images. However, because Google Images are often copyrighted, you can try to avoid violating copyright by using Google's License filter in the Tool's menu.

- How do you create a String vs a Number in JavaScript?
  - To create a string, wrap the value in `' - single quote` or `" - double quote`.
    - `let myString = "String Value"`
  - To create a number, just enter the number without any quotes.
    - `let myNumber = 10`

- What is a Variable and why are they important in JavaScript?  
Variables are containers that hold values that we can use throughout our code. We use variables because it makes our code easier to understand and also allows us to call on it without having to specify a variable over and over again.

## Introduction to HTML

1. What is an HTML attribute?  
An HTML is the part of an HTML Element that contains any additional information such as `class`, `id`, `target`, and `title`.

2. Describe the Anatomy of an HTMl element.  
An HTML Element consists of an opening and closing tag, the content, and an attribute (if applicable).  
For Example:  
`<p class="isAttribute"> I am a Paragraph Element with an attribute of class="isAttribute"</p>`

3. What is the Difference between `<article>` and `<section>` element tags?  
An `<article>` element tag is used for blocks of code on a site that are self-contained components. This includes block posts, news article, product cards, etc. A sections is a generic container for standalone sections in a document that doesnt usually have more specific semantic elements.

4. What Elements does a “typical” website include?  
A typical website contains the following:

``` html
<head> </head>: Contains information about the website not typically visible to the user.  
<body>: The section of the website that is visible to the user which is broken down into the following:   
  - <header>
  - <nav>
  - <main>
  - and <footer>
```

5. How does metadata influence Search Engine Optimization?  
Metadata are not not displayed on the page but they are used by search engines (such as Google) to get keywords and other information and displays/boosts them when a search is executed.

6. How is the `<meta>` HTML tag used when specifying metadata?  
One way to use the `<meta>` tag is to specify the characer set that we can use in the document eg. `<meta charset="utf-8"/>`

## Miscellaneous

### How to start to design a website

- What is the first step to designing a Website?  
The first step to designing a website is: Define the goal/objective of the website.

- What is the most important question to answer when designing a Website?  
The most important question to ask is "What exactly do I want to accomplish?

### Semantics

- Why should you use an `<h1>` element over a `<span>` element to display a top level heading?  
While we can style both the `<h1>` and the `<span>` to look like top level headings, using the Header tag can give it a better semantic value over the span tag. Using h1 tags tell screen readers what a line of text is, and it could also helps with SEO Rankings because it can tell which part of the page are important.

- What are the benefits of using semantic tags in our HTML?  
Some benefits of using semantic tags in our HTML is that it makes the code alot easier to read, they make a page alot easier for the visually impaired users, and also helps increase SEO Rankings.

### What is JavaScript

Describe 2 things that require JavaScript in the Browser?  
Two things in a browser that would require JavaScript are interactive elements such as forms, and timers.

How can you add JavaScript to an HTML document?  
JavaScript can be added two ways, one is by linking an external `.js` file  using  
`<script src ="file.js"></script>`.

Another way is to add the js content in the script elements  
`<script> let js='I am a script code inside an html' </script>`

## Things I want to know more about

- GeoLocation API and how to implement in an app
- When would it be an okay use of `<div>` over `<section>` or `<article>`?
- What is a better use? Inline JavaScript handler or event listener?
