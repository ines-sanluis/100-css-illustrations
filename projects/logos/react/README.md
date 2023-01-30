

# React
- [Preview](#preview)
- [Key concepts](#key-concepts)
- [Credits](#credits)
- [Breaking it down](#breaking-it-down)
- [What I learnt](#what-i-learnt)

## Preview
![React](./preview.png)

## Key concepts
- It's possible to use pseudo-elements to hide part of their ascendant or other elements.
- `transform: translate(-50%, -50%)` is required if you want the center of an element to line up with the center of its parent whenever `top: 50%; left: 50%` is used to move the top left corner of the element to the center of its parent.

## Credits

This illustration was coded following a [Udemy course](https://www.udemy.com/course/creative-css-drawing-course-make-art-with-css) created by [Ahmed Sadek](https://www.udemy.com/user/ahmed-el-sayed-sadek/).

## Breaking it down
Creating an illustration with CSS becomes much easier once you're able to break down the design into smaller elements that are easier to implement. For example, for this illustration I identified four main elements:
- **Horizontal oval**.
- **Left oval**.
- **Right oval**.
- **Center circle**.

## What I learnt

Thanks to this illustration I dived deeper into the meaning of the `box-sizing` property. It sets how the total width and height of an element is calculated. More specifically, `border-box` tells the browser to account for any border and padding in the values you specify for an element's width and height. If you set an element's width to 100 pixels, that 100 pixels will include any border or padding you added, and the content box will shrink to absorb that extra width.

When it comes to shapes, this is an easy and straightforward animation.
