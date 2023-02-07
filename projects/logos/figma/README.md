

# Figma

- [Figma](#figma)
  - [Preview](#preview)
  - [Key concepts](#key-concepts)
  - [Credits](#credits)
  - [Breaking it down](#breaking-it-down)
  - [What I learnt](#what-i-learnt)

## Preview
![Figma](./preview.png)

## Key concepts
- `overflow` property controls what happens to content that is too big to fit into an area.
- With the `hidden` value, overflow is clipped, and the rest of the content will be invisible.

## Credits
This illustration was coded following a [Udemy course](https://www.udemy.com/course/creative-css-drawing-course-make-art-with-css) created by [Ahmed Sadek](https://www.udemy.com/user/ahmed-el-sayed-sadek/).

## Breaking it down
Creating an illustration with CSS becomes much easier once you're able to break down the design into smaller elements that are easier to implement. For example, for this illustration I identified five main elements:
- **Red part of the F**.
- **Purple part of the F**.
- **Green part of the F**.
- **Salmon part of the F**.
- **Blue part of the F**.

Once you establish what are the different elements you need to draw, it is time to think about what shapes they might correspond with. Some figures might be harder to break down and it might help to imagine them in their most basic shapes, in other words, without taking account the radius of the element's corners. 

In this case, here's the mental model I used to implement this illustration:
Element | Basic shape | Final shape
--- | ---
Red part of the F | Circle | Rectangle and circle
Purple part of the F | Circle | Rectangle and circle
Green part of the F | Circle | Rectangle and circle
Salmon part of the F | Circle | Rectangle and circle
Blue part of the F | Circle | Circle

## What I learnt

Thanks to this illustration I dived deeper into the meaning of the `flex-wrap` property. It sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

Setting the value `wrap` implies that flex items break into multiple lines.
