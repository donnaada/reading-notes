# 🗒️ Class 05: Design web pages with CSS

## What is CSS

CSS Stands for Cascading Style Sheets. CSS is used to style a website.

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
