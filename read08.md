# CSS Layout


### Normal Flow

_In normal flow, boxes are displayed one after another based on the Writing Mode of the document. This means that if you have a horizontal writing mode, one in which sentences run left to right or right to left, normal flow will display the boxes of block level elements one after the other vertically down the page_

### Floats
Floats are used to shift a box to the left or right, allowing content to display wrapped around it.

In order to float an item, use the CSS property float and a value of left or right. The default value of float is none.


### CLEARING FLOATS


Once you have floated an element, all of the following elements will wrap around that floated element until they wrap underneath and normal flow continues. If you want to prevent that, you need to clear the float.

On the element that you want to begin displaying after the float, add the property clear with a value of left to indicate clearing an item floated left, right to clear an item floated right, or both to clear any floats.

###  Positioning

To remove an element from normal flow or shift it around from its place in normal flow, you can use the position property in CSS. When in normal flow, elements have a position of static. The items display one after the other in the Block dimension and if you scroll the page they scroll with it.


### Flex Layout

Flexible Box Layout (Flexbox) is a layout method designed for one-dimensional layout. One-dimensional means that you wish to lay out your content in a row, or as a column. To turn your element into a flex layout, you use the display property with a value of flex.

### DIRECTION AND ORDER

Flexbox gives you the ability to change the direction of items on the main axis by using a flex-direction value of row-reverse or column-reverse.

THE FLEX PROPERTIES
The flex properties are how to control the ratios of flex items along the main axis. The three properties are:

- flex-grow
- flex-shrink
- flex-basis
