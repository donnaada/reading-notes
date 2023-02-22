# 🗒️ Class 01: Learning Markdown

## What is Markdown

Markdown is a markup language that allows adding formatting elements to plain text documents. An `.md` extension would mean that the file is a Markdown File.

## Why use Markdown

Markdown is future proof. Meaning that if at some point in the future the website or application can stops working, we would still be able to open the using using any text editor.

## Sample Markdown Syntax

### Headings

To create Header title, you would simply add `#` and a `space` in front of the title. The number of `#` will determine the size. The largest Heading has one 1 ie `# This is the Largest Heading`
> Output: # This is the Largest Heading
and the smallest heading will have six (6) ie `###### This is the smallest heading`
> Output: ##### This is the smallest heading.

### Emphasizing Text

Here are a couple of ways to add emphasis to a text or span of text.

1. Making a text **BOLD**. This can be accomplished by sorrounding your text between a set of double asterisks or double underline `** Bold Text **` or `__ this is also a bold text __`
2. Making a text *Italic*. This can be done by sorrounding your text with a single asterisk or a singe underline.`*Italic Text*` or `_Also italic text_`

**Note** Best practices for italicizing or making a text bold is to use `*` over using the `_`.

*Read more on adding emphasis at*: [https://www.markdownguide.org/basic-syntax/#emphasis](https://www.markdownguide.org/basic-syntax/#emphasis)

### Creating a Link with Markdown

The syntax to create a link in Markdown requires two parts. The Link Text and the URL.

``` markdown
[link text](url)
eg. Here is the link [For Google](https://www.google.com)
```

The output for the example above looks like this: Here is the link [For Google](https://www.google.com). The For Google text is now a clickable link that will take us to the url we inserted in between the parenthesis.

### Creating an Unorderd List with Markdown

Creating an unorder (bulleted) list in markdown is simple. All you would need to do is add a dash `-`, an asterisk `*`, or a plus sign `+` in front of each line item. If you want to create a nested item, insert a `tab` on a new line then add a delimiter before the nested item While you can mix and match the three symbols and still get the same result, it is best practice to pick one delimtier and stick with it.

``` markdown
- Item 1
- Item 2
  - Nested Item 
  - Another Nested Item
- Item 3
```

Output:

- Item 1
- Item 2
  - Nested Item
  - Another Nested Item
- Item 3
