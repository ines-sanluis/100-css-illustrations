# Heart envelope

- [Preview](#preview)
- [Credits](#credits)
- [Key concepts](#key-concepts)
- [Breaking it down](#breaking-it-down)
- [What I learnt](#what-i-learnt)
  - [Shapes](#shapes)
  - [Animation](#animation)
- [Code snippets](#code-snippets)
- [Resource links](#resource-links)

## Preview
![Heart envelope](./preview.png)

## Credits

This illustration was coded following a [Udemy course](https://www.udemy.com/course/creative-css-drawing-course-make-art-with-css) created by [Ahmed Sadek](https://www.udemy.com/user/ahmed-el-sayed-sadek/).
## Key concepts
- Breaking down the illustration into smaller elements helps approach the implementation.
- Animating.
- Transforming.
- Pseudo-elements.

## Breaking it down
Creating an illustration with CSS becomes much easier once you're able to break down the design into smaller elements that are easier to implement. For example, for this illustration I identified two main elements:
- The **envelope**. It has three folds.
- The **heart**. It's made out of three rectangles and has a heartbeat.

Once you establish what are the different elements you need to draw, it is time to think about what shapes they might correspond with. Some figures might be harder to break down and it might help to imagine them in their most basic shapes, in other words, without taking account the radius of the element's corners.

![Heart envelope shapes](./shapes.pngg)

In this case, here's the mental model I used to implement this illustration:
| Element | Basic shape | Final shape
|---|---|---|
|Envelope|Rectangle|Rectangle
|Envelope fold|Triangle|Triangle
|Heart|Three squares|Heart

## What I learnt

### Shapes
I realized that it is much easier to implement an illustration if I'm able to break it down into smaller and easier to implement elements.

### Animation

Using the `animation` property and the `keyframes` at-rule to make the rocket move around the moon allowed me to consolidate my knowledge on the right syntaxis.

## Code snippets
Animation syntax

```
    animation: animation-name speed iteration-count direction;
```

Keyframes syntax

```
    @keyframes animationname {keyframes-selector {css-styles;}}
```
## Resource links
[Transform](https://www.google.com/search?channel=fs&client=ubuntu&q=transform+css)
