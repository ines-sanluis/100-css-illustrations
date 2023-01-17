

# Pacman

- [Preview](#preview)
- [Credits](#credits)
- [Breaking it down](#breaking-it-down)

## Preview
![Pacman](./preview.png)

## Credits

This illustration is an original work inspired by the Pacman videogame.

## Breaking it down
Creating an illustration with CSS becomes much easier once you're able to break down the design into smaller elements that are easier to implement. For example, for this illustration I identified five main elements which do not use these shapes use `clip-path` or `svg` tags:
- **Pacman**.
- **Food**.
- **Ghost**.

Once you establish what are the different elements you need to draw, it is time to think about what shapes they might correspond with. Some figures might be harder to break down and it might help to imagine them in their most basic shapes, in other words, without taking account the radius of the element's corners. 

In this case, here's the mental model I used to implement this illustration:
Element | Shape | Implementation details
--- | --- | ---
Pacman | Circle | Border attribute
Food | Circle |
Ghost body | Rectangle |
Ghost feet | Circle |
Ghost eyes | Circle |
