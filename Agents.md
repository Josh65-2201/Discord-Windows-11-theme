# Theme formatting requirements

## Agents instructions

- DO NOT run Python or PowerShell script for writing to the file.
- DO edit all files directly so that VS Code diff editor will be shown.
- DO attempt to do all of the file at the same time. If it's not possible, do it in stages one after the other.

## File formatting instructions

- DO NOT add or remove any CSS rules or properties.
- DO NOT alter any property values, selectors, or comments.
- DO NOT alter `@import` statements or the file header comment block.
- DO NOT remove indentation level.
- DO make sure all CSS properties lines have `;` at the end.
- DO add new lines before comments following the below layout

```txt
 1|Main section 1 (E.G. Servers bar, Messages content)
 2|  Sub section 1 (E.G. Server icon, Message)
 3|    Part 1 (Position, Background color)
 4|
 5|    Part 2 (Position, Background color)
 6|
 7|
 8|  Sub section 2 (E.G. Server icon, Message)
 9|
10|
11|
12|
13|
14|Main section 2 (E.G. Servers bar, Messages content)
```

### Property Order

Sort properties within every CSS rule block in this exact category order.

- display
- visibility
- overflow
- position
- top
- left
- right
- bottom
- z-index
- align
- max-width
- min-width
- width
- max-height
- min-height
- height
- line-height
- padding
- padding-*
- margin
- margin-*
- border
- border-radius
- background
- background-color
- background-image
- background-repeat
- color
- opacity
- transform
- transition
- animation
- Everything else not listed above
