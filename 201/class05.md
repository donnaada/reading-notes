# 🗒️ Class 05

The topics covered in the reading are important to get an understanding more of how we can make our site more accessible to the public and visually appealing

## Learning HTML

- What is a real world use case for the alt attribute being used in a website?
  - The alt attribute displays a description of the image and is used in the event that an image cannot load. It is also there for the visually impared users who use a screen reader to read out the image.

- How can you improve accessibility of images in an HTML document?
  - We can improve accessibility of the images in a HTML document by using the alt attribute and making sure that the alt attribute properly describes the image.

- Provide an example of when the figure element would be useful in an HTML document.
  - We can use the figure element to display an image as well as the caption for that specific image.
  
- Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
  - Gifs are a like a mix of pictures and videos. SVGs are the better choice for images because it can be modified using drawing commands like changing color.

- What image type would you use to display a screenshot on your website and why?
  - The image types we would use to display screenshots are .png and .jpg/.jpeg extensions.

## Learning CSS

- Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
  - Foreground color is the color of html elements and background color is the color of the HTML background.

- Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
  - I would use apps like [Paletton](https://www.paletton.com/) to simulate different color schemes agains a current palette and adjust from there.

- What should you consider when choosing fonts for an HTML document?
  - Make sure you are using websafe fonts and it matters what order you list your fonts. Unlike CSS rules, browsers will try and use the first font file and then try for the second font file and so on.

- What do font-size, font-weight, and font-style do to HTML text elements?
  - Adjusts how big/small a text is, how bold, and whether its italics, underline etc.

- Describe two ways you could add spacing around the characters displayed in an h1 element.
  - Using Margin and Padding
  - using Letter Spacing and wordspacing

## Things I Want to learn

- Read more into accessibility and create standard template/palletes

## Git Branching

`Main Branch` is the production branch

### Feature Branch

Reviewed first then merged into main using Pull Request.

### Fun With Functions

create template first

1. git clone (Main on Github)
2. Create a feature branch called `sum` - `git checkout -b sum`
3. Write code
4. Add and Commit
5. push to github on `sum branch` - git push origin sum
6. open PR from sum on main on github
7. `git checkout main` to switch back to main branch
8. run `git pull origin main` to get all the change