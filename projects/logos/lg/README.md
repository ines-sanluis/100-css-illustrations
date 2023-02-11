# LG

- [Preview](#preview)
- [Key concepts](#key-concepts)
- [Credits](#credits)
- [Breaking it down](#breaking-it-down)
- [What I learnt](#what-i-learnt)

## Preview
![LG](./preview.png)

## Key concepts
- `transform: translate(-50%, -50%)` is required if you want the center of an element to line up with the center of its parent whenever `top: 50%; left: 50%` is used to move the top left corner of the element to the center of its parent.
- Transforming.
- Positioning.

## Credits
This illustration was coded following a [Udemy course](https://www.udemy.com/course/creative-css-drawing-course-make-art-with-css) created by [Ahmed Sadek](https://www.udemy.com/user/ahmed-el-sayed-sadek/).

## Breaking it down
Creating an illustration with CSS becomes much easier once you're able to break down the design into smaller elements that are easier to implement. For example, for this illustration I identified five main elements:
- **Container**.
- **Letter L**. Consists of two lines.
- **Letter G**. Consists of a curved line and an horizontal line.
- **Small circle between them**.

Once you establish what are the different elements you need to draw, it is time to think about what shapes they might correspond with. Some figures might be harder to break down and it might help to imagine them in their most basic shapes, in other words, without taking account the radius of the element's corners. 

In this case, here's the mental model I used to implement this illustration:
Element | Shape
--- | ---
Container | Circle
Letter L | One vertical line and one horizontal line
Letter G | A curved line and an horizontal line
Small circle between them | Circle

## What I learnt

Thanks to this illustration I solidified my knowledge of transformations and positioning.
