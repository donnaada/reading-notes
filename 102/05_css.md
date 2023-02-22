# 🗒️ Class 05: Design web pages with CSS

## What is CSS

CSS Stands for Cascading Style Sheets. CSS is used to style a website. Here is an example of CSS Code

``` css
h1 {
color: goldenrod;
font-size: 2rem;
}
```

Css is made up of 2 parts - the selector and the declaration. In the example above, `h1` is the selector and `color: goldenrod;` is the declaration. The declaration can be broken into two parts. To the left of the `:` is the property(`color`), and to the right is the property value(`goldenrod`). 

Three things to remember

* The declarations must be wrapped in curly braces after the selector.
* If there are multiple declarations, we must use `;` to separate the different sectors, and
* we must also use a `:` to separate the property from its value.

We can also select multiple selector. all we would have to do is add a commas between them.

``` css
h1,
.header-text,
.page-title {
color: goldenrod;
font-size: 2rem;
}
```

## Three (3) ways to insert CSS into your project

* External Styles

``` html
<link rel="stylesheet" href="style.css">
```

* Internal Styles

``` html
<style>
  .class{
    font-weight: 600;
  }
</style>
```

* Inline Style

```html
<p style="color: red;"> Red Paragraph </p>
```

## CSS rule that would give all `<p>` elements red text

``` css
p {
color: red;
}
```

## Different ways to add color to an element

* Color name ie `red`, `blue`, `green`
* HEX - a hex value ie `#ffffff` or `#000000`
* rgb(red-value,green-value,blue-value) - RGB stands for Red Green Blue and the values in the parenthesis can range from 0-255 ie `rgb(255,0,0)` will give you the color red.
* rgba(r,g,b,opacity-value) - similar to rgb but the value gives control over opacity ie `rgba(255,0,0,0.5)` will give you the color red at 50% opacity.
* hsl() - hsl takes three values representing hue, saturatoin, and lightness ie `hsl(0, 100%, 50%)` is the color red
* hsla() - similar to rgba, hsla gives control over the opacity of the hsl value `hsla(0,100%,50%,0.25)` will result in a color with 25% opacity
* mix() - allows you to mix two colors together, with an optional weight parameter ie `mix(red, blue)`
