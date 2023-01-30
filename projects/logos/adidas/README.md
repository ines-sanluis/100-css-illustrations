

# Adidas
- [Adidas](#adidas)
  - [Preview](#preview)
  - [Key concepts](#key-concepts)
  - [Credits](#credits)
  - [Breaking it down](#breaking-it-down)
  - [What I learnt](#what-i-learnt)

## Preview
![Adidas](./preview.png)

## Key concepts
- `overflow` property controls what happens to content that is too big to fit into an area.
- With the `hidden` value, overflow is clipped, and the rest of the content will be invisible.

## Credits

This illustration was coded following a [Udemy course](https://www.udemy.com/course/creative-css-drawing-course-make-art-with-css) created by [Ahmed Sadek](https://www.udemy.com/user/ahmed-el-sayed-sadek/).

## Breaking it down
Creating an illustration with CSS becomes much easier once you're able to break down the design into smaller elements that are easier to implement. For example, for this illustration I identified four main elements:
- **First column**.
- **Second column**.
- **Third column**.

Once you establish what are the different elements you need to draw, it is time to think about what shapes they might correspond with. Some figures might be harder to break down and it might help to imagine them in their most basic shapes, in other words, without taking account the radius of the element's corners. 

In this case, here's the mental model I used to implement this illustration:
Element | Shape
--- | ---
First column | Rectangle
Second column | Rectangle
Third column | Rectangle

## What I learnt

Thanks to this illustration I dived deeper into the meaning of the `box-sizing` property. It sets how the total width and height of an element is calculated. More specifically, `border-box` tells the browser to account for any border and padding in the values you specify for an element's width and height. If you set an element's width to 100 pixels, that 100 pixels will include any border or padding you added, and the content box will shrink to absorb that extra width.

When it comes to shapes, this is an easy and straightforward animation.