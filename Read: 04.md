# HTML Links, CSS Layout, JS Functions

## HTML Links
links are important because it enables the very idea of browsing or surfing. It allow you to move from one web page to another.

**how to write the link statement in HTML page?**

\<a href="http://www.google.com"> Google \</a>

we use the previous syntax if we want to link to other web site, but if want tp link to a page in the same project we just write the  page name.extension instead of http... , like:

\<a href="contact.html"> Contact us \</a>

notice that the content between the open and close tag is the words that the user will click on, to open the link. 

if we want to link with a file outside the folder that we are in, we just put double dots and backslash (../) before the link.

such as: \<a href="../contact.html"> Contact us \</a>

if we want to link to an email we use the "mailto" key word.

like: \<a href="mailto:jon@example.org"> Email Jon \</a> 

there are some useful attributes that can make our sites simpler, such as the target attribute which allow us to define where we want to open the link.

if we want to open it in a new window we put the value (_blank)

for example: \<a href="http://www.imdb.com" target="_blank"> IMBD \</a>

if we want to link to a specific part of the same page or another page we give the element that we wantto link to an id, after that we write the link statment as we explain above, we just change the href value to "#ID_Name".

for example: \<a href="#prologue">Prologue\</a>

## CSS Layout

boxes in HTML are either a block-level box or an inline box.

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

CSS has the following positioning schemes that allow you to control the layout of a page:

1. **Normal flow:** Every block-level element appears on a new line. (This is the default behavior)

2. **Relative Positioning:** This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. 

3. **Absolute positioning:** Absolutely positioned elements move as users scroll up and down the page.

To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed.

- **Fixed Positioning:** this is a form of absolute positioning that positions
the element in relation to the browser window, as opposed to the containing element.

Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

- **Floating Elements:** floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box.

The floated element becomes a block-level element around which other content can flow.

## JS Functions

 Programmers use functions, methods, and objects to organize their code. 

**Functions & Methods**

- Functions consist of a series of statemnts that have been grouped together because they perform a specific task.

- Methods are the same as a function, except that it created inside an object.

- How to write or declare the function?

function functionName () {

statements;

}

and we have to say that the above declareation is the general, and there are some additional things that we can write.

for example: some functions take values, so we have to declare parameters in it, like :

function functionName (valA, valB) {

value = valA + valB + 10;

return value;
}

and surely when we take arguments we have to return their result, so when we put the return statement in the bottom of the function, after we excecute all of the statements.

**Objects**

- Objects are made up of properties and methods.

**Built-in Objects**

- The browser comes with a set of objects that act like a toolkit for creating interactive web pages. 

## Pair Programming

**What is pair programming?**

it is the practice of two developers sharing a single workstation to interactively tackle a coding task together.

**How does pair programming work?**

it involoves two roles:

1. The Driver: who is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code.

2. The Navigator: uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

**Why we have to follow the pair programming?**

While learning to code, developers likely study several programming languages. So,  there are four fundamental skills that help anyone learn a new language:

1.  Listening: hearing and interpreting the vocabulary.

2. Speaking: using the correct words to communicate an idea.

3. Reading: understanding what written language intends to convey.

4. Writing: producing from scratch a meaningful.

Pair programming touches on all four skills.

**The Results of follow pair programming:**

1. Greater efficiency

2. Engaged collaboration

3. Learning from fellow students

4. Social skills

5. Job interview readiness

6. Work environment readiness













