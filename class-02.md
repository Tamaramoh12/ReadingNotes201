# Some Of HTML
**Texts in HTML**
- Heading: HTML has six levels of headings arranged from the biggest to smallest. \<h1> to \<h6>
  
- Paragraphs: you can type the paragraph you need between this open and close tags. \<p> .... \</p>

- Bold: you have to put your important words between \<b> and \</b>.

- Italic: you have to put your unique words between \<i> and \</i>.

- Sub: We can  use to contain characters that should be subscript. \<sub> .... \</sub>

- Sup: we use to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22. \<sup> ... \</sup>

- To start new line we use \<br/> element. and be careful that it hasn't a close tag.

- we can use \</hr> to make a horizontal line. which is also doesn't have a closing tag.

**The above points from 1 to 8 are called structural markup, which is used to describe both headings and paragraphs**

**The other type of tags is called semantic markup, which provides extra information, such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on**

Before we going deep in the topic I like explain the reason of using the semantic markup, which is: using these elements is that other programs, such as screen readers or search engines, can use this extra information. For example, the voice of a screen reader may add emphasis to the words inside the \<em> element, or a search engine might register that your page features a quote if you use the \<blockquote> element.

- if we put the text between \<strong> and \</strong> it indicates that its content has strong importance, and by  default, browsers will show
the contents in bold.

- The \<em> element indicates emphasis that subtly changes the meaning of a sentence.
and by default browsers will show the contents of an <em> element in italic.
  
 if want to add a quote to our web page, we can use either \<blochquote>  or \<q>.
The first one for the long quotes and the second for the short quotes.

- if we want to add an acronym or abbrevation we can put the text between \<abbr> and \</abbr>

-  To contain contact details for the author of the page we can use \<address> tag.

- To put a line through the text we use \<del> or \<s>

- To put a lineunder the  text we use \<ins>

# Some of CSS

**Block & Inline Elements**
- Block level elements always start on a new line.

Ex: \<h1> to \<h6>, \<p>, \<div>

- Inline elements put the content beside each other.

Ex: \<b>, \<i>, \<img>, \<span>

**CSS Rule**

selector {property: value;}

**How To Use CSS?**

There are three ways to include CSS in our projects:

1. External File
in the head section we add:

\<link href="css/styles.css" type="text/css" rel="stylesheet" />

href refer to the file that include the CSS code.

type specifies the type of document being linked to. The value should be text/css.

rel specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

2. Internal File

we write the CSS code inside the \<style> and \</style> tags which will be located in the head.

3. Inline 

in the tag attributes we put: style = "property:value;"

**CSS Selectors**
- Universal: Applies to all elements in the document.

\* indicates the universal selectors.

- Type: Matches element names. such as h1,p,div { }

- Class: Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol. Ex: .class1 { }

- ID: Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol. Ex: #logo { }

- Child: Matches an element that is a direct child of another. Ex: div>p { }

- Descendant: Matches an element that is a descendent of another specified element (not just a direct child of that element). Ex: div p { }

- Adjacent Sibiling: Matches an element that is the next sibling of another. Ex: h1+p { }

- General Sibiling: Matches an element that is a sibling of another, although it does not have to be the directly preceding element. Ex: h1 ~ p { }


# Some Of Javascript




