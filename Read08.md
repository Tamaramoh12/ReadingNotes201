# CSS Layout

Simply, it is about how to control where each element sits on a page and how to create attractive page layouts.

Before going in the topic, we have to know about **Building Blocks**, so what is it?

CSS treats each HTML element as if it is in its own box. This box will either be a block level box or an inline box.

Block-level elements start on a new line.

Examples include: <h1> <p> <ul> <li>

Inline elements flow in between surrounding text.

Examples include:<img> <b> <i>

CSS has the following positioning schemes that allow you to control the layout of a page:

Normal flow: Every block-level element appears on a new line. (This is the default behavior)

Relative Positioning: This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.

Absolute positioning: Absolutely positioned elements move as users scroll up and down the page.

To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed.

Fixed Positioning: this is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element.
Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

Floating Elements: floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box.
The floated element becomes a block-level element around which other content can flow.



