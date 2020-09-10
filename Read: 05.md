# HTML Images; CSS Color & Text

## HTML Images

**How to choose the right image?**

Images should be:

- relevant

- Convey information

- Convey the right mood
 
- Be instantly recognisable
 
- Fit the color palette

**Tip:** if you build you site from scratch, it is good practice to create a folder for all of the images the site uses. such as the folders you create to manage CSS and JavaScript files.

**How to add an image to the site?**

we put the <img> tag which have only open tag, and inside it we put essintial two attributes which are src and alt.

- src: refers to the images' place.

- This provides a text description of the image which describes the image if you cannot see it.

In addition to the src and alt we also have an optional attributes. such as:

- title: You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.

- height: specifies the height of the image in pixels.

- width: specifies the width of the image in pixels.

- align: The align attribute was commonly used to indicate how the other parts of a page should flow around an image. It has been removed from HTML5 and new websites should use CSS to control the alignment of images. 

The align attribute can take either right or left value. [Note: we use this values to align the images horizontally]


The align attribute can take one of three values (top - middle - bottom) if we want to align the images vertically]

**Where to Place Image in Your Code?**

The image place will affect how the code will display.

Example:

1. before a paragraph The paragraph starts on a new line after the image.

2. inside the start of a paragraph The first row of text aligns with the bottom of the image.

3. in the middle of a paragraph The image is placed between the words of the paragraph that it appears in.

Example: [Example](img code.PNG) , [The result](img result.PNG)

**Three Rules for Creating Images**

1. Save images in the right **format**.

2. Save images at the right **size**.

3. Use the correct **resolution**.

**Tools to Edit & Save Images**

1. Software Programs:

- Adobe Fireworks

- Pixelmator

- PaintShop Pro

- Paint.net

2. Online Editors
- www.photoshop.com

- www.pixlr.com

- www.splashup.com

- www.ipiccy.com

3. Online extra

- Watch videos that demonstrate how to resize images and save them in the correct format using both of these applications.

**Tips to decide which format to use**

- Whenever you have many different colors in a picture you should use a JPEG.
A photograph that features snow or an vercast sky might look like it has large areas that are just white or gray, but the picture is usually made up of many different
colors that are subtly different.

- Use GIF or PNG format when saving images with few colors or large areas of the same color.

**Image Dimensions**

The images you use on your website should be saved at the same width and height that you want them to appear on the page.

When cropping images it is important not to lose valuable information. It is best to source images that are the correct shape if possible.

Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.

Vector images differ from bitmap images and are resolution-independent. Vector images are commonly created in programs such as Adobe Illustrator.

**More about images**

Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations.

Creating an image that is partially transparent (or "see-through") for the web involves selecting one of two formats: Transparent GIF or PNG


**Some from HTML5**

Images often come with captions. HTML5 has introduced a new \<figure> element to contain images and their caption so that the two are associated. 

You can have more than one image inside the \<figure> element as long as they all share
the same caption.

The \<figcaption> element has been added to HTML5 in order to allow web page authors to add a caption to an image.

## CSS Colors 

**how to change color using CSS?**

we use the **color** property assign to oneof three values:

1. rgb values: These express colors in terms of how much red, green and blue are used to make it up. Forexample: rgb(100,100,90)

2. hex codes: These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash #sign. For example: #ee3e80

3. color names:There are 147 predefined color names that are recognized by browsers. For example: DarkCyan.

**how to change backgroud-color using CSS?**

we use the **background-color** property with the same values of color property that we assigned above.

**how to decide which color do you want?**

Every color on a computer screen is created by mixing amounts of red,green, and blue. To find the color you want, you can use **a color picker**.

**something that you must pay attention to:**

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible. which mean that you mush pay attention to contrast, by using a suitable color and background color.

**some from CSS3**

- Opacity: a property that allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).

- HSL colors:  an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.

1. Hue: it is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360.

2. Saturation: is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray.

3. Lightness: is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity.

4. Alpha: This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.

Syntax:

hsl(HUE, Saturation, Lightness)

hsla(HUE, Saturation, Lightness, Alpha)

## CSS Texts

there are many properties that we can apply on texts, such as: typefaces,  color of text, the spacing between words and letters ...

1. Specifying Typefaces: we use the font-family property pecify the typeface that should be used for any text inside the element(s). The value of this property is the name of the typeface you want to use. 

2. Size of Type: we use the font-size property  to specify a size for the font.

There are several ways to specify the size of a font. The most common are: pixels, percentages, ems.

*More Font Choice @font-face*

@font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.

syntax:

@font-face {

font-family: 'ChunkFiveRegular';

src: url('fonts/chunkfive.eot');

}

h1, h2 {

font-family: ChunkFiveRegular, Georgia, serif;

}

font-family: This specifies the name of the font. This name can then be used as a value of the font-family property in the rest of the style sheet (as shown in the rule for
the \<h1> and \<h2> elements).
 
src: This specifies the path to the font.

format: This specifies the format that the font is supplied in. 

3. bold: we use the font-weight property to create bold text. There are two values that this property commonly takes: 

normal This causes text to appear at a normal weight.

bold: This causes text to appear bold.

4. italic: we use the font-style property for it. There are three values this property can take:

normal: This causes text to appear in a normal style (as opposed to italic or oblique).

italic: This causes text to appear italic.

oblique: This causes text to appear oblique.

5. UpperCase & LowerCase: The text-transform property is used to change the case of text giving it one of the following values:

uppercase: This causes the text to appear uppercase.

lowercase: This causes the text to appear lowercase.

capitalize: This causes the first letter of
each word to appear capitalized

6. Underline & Strike: The text-decoration property allows you to specify the following values:

none: This removes any decoration already applied to the text.

underline: This adds a line underneath the text.

overline: This adds a line over the top of the text.

line-through: This adds a line through words. 

blink: This animates the text to make it flash on and off (however this is generally frowned upon, as it is considered rather annoying).

7. Leading: we use the line-height property to set the height of an entire line of text, so the difference between the fontsize and the line-height is equivalent to the leading (as shown in the diagram above). Increasing the line-height makes the vertical gap between lines of text larger.

8. Letter & Word Spacing: You can control the space between each letter with the letter-spacing property. Also You can also control the gap between words using the word-spacing property. 

9. Alignment: The text-align property allows you to control the alignment of text. The property can take one of four values:

left: This indicates that the text
should be left-aligned.

right: This indicates that the text should be right-aligned.

center: This allows you to center text. 

justify This indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box

10. Vertical Alignment: The vertical-align property is a common source of confusion. It is not intended to allow you to vertically align text in the middle of block level  elements such as \<p> and \<div>, although it does have this effect when used with table cells (the \<td> and \<th> elements).

It is more commonly used with inline elements such as \<img>, \<em>, or \<strong> elements. When used with these elements, it performs a task very similar to the HTML align attribute used on the \<img> element. The values it can take are:



