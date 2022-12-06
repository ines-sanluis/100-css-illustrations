

# Rainbow

- [Rainbow](#rainbow)
  - [Preview](#preview)
  - [Credits](#credits)
  - [Key concepts](#key-concepts)
  - [Breaking it down](#breaking-it-down)
  - [What I learnt](#what-i-learnt)
    - [calc()](#calc)
    - [em](#em)
  - [Code snippets](#code-snippets)
  - [Resource links](#resource-links)

## Preview
![Rainbow](../../../images/rainbow.png)

## Credits

This illustration was coded slightly modifying a [YouTube tutorial](https://www.youtube.com/watch?v=YG9FyEDGDVM) made by [Mitali Jadhavrao](https://codingartistweb.com/about/).

## Key concepts
- It's possible to use an element to hide part of another/s. This illustration uses this concept to convert full circles into half circles.asd
- `transform: translate(-50%, -50%)` is required if you want the center of an element to line up with the center of its parent whenever `top: 50%; left: 50%` is used to move the top left corner of the element to the center of its parent.
- `calc() ` function lets you perform calculations when specifying CSS property values.
-  The `em` and `rem` units are practical in creating perfectly scalable layout.

## Breaking it down
Creating an illustration with CSS becomes much easier once you're able to break down the design into smaller elements that are easier to implement. For example, for this illustration I identified five main elements:
- The **red stripe**.
- The **orange stripe**.
- The **yellow stripe**.
- The **green stripe**.
- The **blue stripe**.

Once you establish what are the different elements you need to draw, it is time to think about what shapes they might correspond with. Some figures might be harder to break down and it might help to imagine them in their most basic shapes, in other words, without taking account the radius of the element's corners.

In this case, here's the mental model I used to implement this illustration:
| Element | Basic shape | Final shape
|---|---|---|
|Red stripe|Circle|Half circle
|Orange stripe|Circle|Half circle
|Yellow stripe|Circle|Half circle
|Green stripe|Circle|Half circle
|Blue stripe|Circle|Half circle

## What I learnt

### calc()
The calc() CSS function lets you perform calculations when specifying CSS property values. It takes a single expression as its parameter, with the expression's result used as the value. The expression can be any simple expression combining the following operators: addition, subtraction, multiplication and division.

The + and - operators must be surrounded by whitespace. While  * and / do not require it.

### em
CSS has several different units for expressing a length, which might be:
- Absolute. The absolute length units are fixed and a length expressed in any of these will appear as exactly that size.
- Relative. Relative length units specify a length relative to another length property. Relative length units scale better between different rendering medium.

The `em` unit is a relative length relative to the font-size of the element. The `em` and `rem` units are practical in creating perfectly scalable layout.

## Code snippets
`top: calc(50% + 5.62em);`
## Resource links
[Calc](https://developer.mozilla.org/en-US/docs/Web/CSS/calc)