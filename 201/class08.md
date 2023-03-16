# 🗒️ Class 08: CSS Layouts

## Learn CSS - Flexbox

- Flexbox is designed for one-dimensional content. Explain what this means.

    > This mean that instead of having to do media quiries for the browser to adher to, you can add flexbox properties/boundaries to give the browser an idea of how we want the content displayed

- Explain the difference between the main axis and cross axis.

    > The main axis is the default `flex-direction` property. Flex displays elements from left to right. the cross axis displays the direct children elements in column formatting.

- How can using certain properties of flexbox negatively impact accessibility?

    > We need to be careful with certain properties like row-reverse or column-reverse beecuase these only chnage the visual order and not the logicla order.

## CSS Layout - Flexbox

- What are some advantages of using flexbox over float?

    > flexbox gives us a more options to simplify content on a page or in a continer. With flexbox, we can specify what direction we want something to go, how tall and wide we want the children to be, and spacing between each direct child element.

- How does this topic connect with your long term goals?

    > Flex boxes will help make things a lot more responsive and will allow us to create better starter template that can make getting started on a new project alot quicker.

## Lecture Notes

### Prototypal Inheritence

An object inherited by every other object created by a constructor.

function Constructor1(arg){
    this.arg = arg;
}

function Constructor2(arg1, arg2, arg3){
    Constructor1.call(this, arg3)
    this.arg1 = arg1;
    this.arg2 = arg2;

}

### Flex Boxes

used to create responsive row/column layouts

align items is on the opposite axis
justify-content is on the same axis
