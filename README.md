# Grid Structure Ass-9 CSS


## Project Description
This project demonstrates a grid-based webpage layout using HTML and CSS. The layout consists of a navigation bar and a grid of images.

## HTML Structure

### Navigation Bar (`div.nav`)
The navigation bar contains a set of buttons that provide navigation links.
![image](https://github.com/saifulislam05/grid-structure/assets/73392705/23fa9f70-4fe8-49c8-b381-2b62db22ce6c)

- `div.nav`: The navigation bar container.
  - `button`: Navigation buttons with a black background and white text.

### Image Grid
The project displays a grid of images using CSS Grid.
![image](https://github.com/saifulislam05/grid-structure/assets/73392705/59b58c40-5ac5-4094-9547-90ee77f1edc7)

- `div.wrapper`: The main wrapper for the grid layout.
  - `.item`: Individual grid items containing images.
    - `.item1`: Spans the entire width of the grid.
    - `.item2`, `.item3`, `.item4`, `.item5`: Grid items spanning different columns and rows.
    - `.item6`, `.item7`, `.item8`, `.item9`, `.item10`: More grid items with different positions.

## CSS Styles

### Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.
- `box-sizing: border-box;`: Ensures elements include padding and borders in their total width.

### Navigation Bar (`div.nav`)
- `.nav`: The navigation bar container.
  - `display: flex;`: Arranges navigation buttons in a row.
  - `width: 60%;`: Sets the width of the navigation bar.
  - `justify-content: space-between;`: Separates buttons with space.
  - `align-items: center;`: Vertically centers items.

- `.nav button`: Navigation buttons.
  - `background-color: black;`: Sets the background color.
  - `color: white;`: Sets the text color.
  - `padding: 5% 40%;`: Adds padding.
  - `border-radius: 8px;`: Rounds the corners.

### Image Grid (`.item`)
- `.item`: Individual grid items containing images.
  - `border: 1px solid white;`: Adds a white border.
  - `margin: 2px;`: Adds margin.
  - `padding: 2px;`: Adds padding.
  - `background-color: white;`: Sets the background color.

- Positioning for specific grid items:
  - `.item1`: Spans the entire width of the grid.
  - `.item2`, `.item3`, `.item4`, `.item5`: Grid items spanning different columns and rows.
  - `.item6`, `.item7`, `.item8`, `.item9`, `.item10`: More grid items with different positions.

