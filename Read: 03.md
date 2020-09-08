# HTML Lists, CSS Boxes, JS Control Flow

## Lists in HTML.

**List Types**

**1. Order Lists**

The ordered list is created with the \<ol> element, and we use it whenever we need a numbered list, to follow the steps one by one or for any other reason.

[Example](ol.PNG)

**2. Unorder Lists**

The unordered list is created with the \<ul> element. and it begins with a bullet point or other characters like circle point or square point. 

[Example](ul.PNG)

**Note:** Each item in the ordered or unordered lists is placed between an opening \<li> tag and a closing \</li> tag. (The li stands for list item.)

**3. Definition Lists**

It is the type of lists that made up of a set of terms along with the definitions for each of those terms. and it is created with the \<dl> element and usually consists of a series of terms and their definitions.
  
Inside the \<dl> element we use pairs of \<dt> and \<dd> elements.

\<dt> is used to contain the definition term.

\<dd> is used to contain the definition.

[Example](dl.PNG)

**Nested Lists**

we can put list inside one another.

[Example](nested.PNG)

## Boxes in CSS

To set our own dimensions for a box we can use the height and width properties. By using  pixels, percentages, or ems. 

The **min-width and min-height** properties specifiy the smallest size a box can be displayed at when the browser window is narrow.

The **max-width and max-height** properties indicate the maximum width and maximum height a box can stretch to when the browser window is wide.

**overflow property** tells the browser what to do if the content contained within a box is larger than the box itself.

**overflow values:**
1. hidden:  hides any extra content that does not fit in the box.
2. scroll: adds a scrollbar to the box so that users can scroll to see the missing content.

**Borders** Every box has a border (even if it is not visible or is specified to be 0 pixels wide).

**Margin** sit outside the edge of the border. 

**Padding** is the space between the border of a box and any content contained within it. 

**more about border properties:**

**1. border-width** property is used to control the width of a border. The value of this property can either be given in pixels or using : (thin, medium, or thick)

**2. border-style** This property can take several values: (solid,dotted, dashed, double, groove, ridge, inset, outset, hidden/none )

**3. border-color** we can specify the color of a border using either RGB values, hex codes or CSS color names.

we can specify all the border properties in one statement using this synatx:

border: width style color;

Ex:  border:3px solid blue;

**centering content:** if we want to center a box on the page (or center it inside the element that it sits in), we can set the left-margin and right-margin to auto.

**Block & Inline Display:** we can simply change the display for any element by using the display property which take three values: inline, block, inline-block, none.

The **visibility** property allows us to hide boxes from users but It leaves a space where the element would have been. and it take two values: hidden and visible.

**Introduction to CSS3**

The **border-image property:** applies an image to the border of any box. It takes a background image and slices it into nine pieces. 

The **box-shadow property** allows you to add a drop shadow around a box. It must
use at least:

1. Horizontal offset: negative values position the shadow to the left of the box.

2.Vertical offset: negative values position the shadow to the top of the box.

The **border-radius property:** which introduces the ability to create rounded corners on any box. The value indicates the size of the radius in pixels.

## JS Control Flow







