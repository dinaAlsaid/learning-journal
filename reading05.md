# Code 102

[previous](https://dinaalsaid.github.io/learning-journal/reading04)
[Home](https://dinaalsaid.github.io/reading-notes/)
[next](https://dinaalsaid.github.io/learning-journal/reading06)

## CSS

### using CSS with HTML

there are three ways:

* link using the link tag/element (external)
* write CSS code in a style tag (internal)
* from the style attributes in any element's tag

using external CSS stylesheet will give you the advantage of applying the same style to  all you website pages, less code to write, and faster site load.

### CSS selectors

types of selectors:

* universal: `* {}`
* type: `p, h1, div{}`
* class: `.className1 {}`
* ID: `#IDname1 {}`
* child: `li >a {}`
* descendant: `p a {}`

## Adding color

when using color in you CSS code you can specify it in three ways: color name, RGB values, HSL vaules and Hex code.

### Color theory 101

color is usualy described by 3 main things:

* hue: is the color blue, green...etc. ?
* saturation: how pure is the color?
* brightness: how much white or black is in the color?

![color](https://i.stack.imgur.com/PvK4n.png)

you can get a specific color by tweeking these values.

### Effects using CSS

other things you can do with color in css is change its opactiy. meaning, making the color see through. using the opacity property, or defining the color using rgba (red green blue opacity).

![opacity](https://community.adobe.com/legacyfs/online/1775293_opecity.png)