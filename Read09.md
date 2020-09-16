# Forms and Events

### HTML Forms

Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.

HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.

**How Forms Work?**

1- A user fills in a form and then presses a button to submit the information to the server.

2- The name of each form control is sent to the server along with the value the user enters or selects.

3- The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.

4- The server creates a new page to send back to the browser based on the information received.

**Form Structure**

\<form>

Form controls live inside a \<form> element. This element should always carry the action attribute and will usually have a method and id attribute too. 

action

Every \<form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

method

Forms can be sent using one of two methods: get or post.

**Form Inputs:**

1- Text Input:

The <input> element is used to create several different form controls.

The value of the type attribute determines what kind of input they will be creating.

type="text"

When the type attribute has a value of text, it creates a singleline text input.

name

When users enter information into a form, the server needs to know which form control each piece of data was entered into.

Ex: in a login form, the server needs to know what has been entered as the username and what has been given as the password.) Therefore, each form control requires a name attribute.

The value of this attribute identifies the form control and is sent along with the information they enter to the server.

maxlength

You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter.

Ex: if you were
asking for a year, the maxlength
attribute could have a value of 4.

2- Password Input

3- Text Area

4- Radio Button

5- Checkbox

6- Drop Down List Box

7- Multiple Select Box

8- File Input Box

9- Submit Button

10- Image Button

11- Button & hidden Controls

12- Labelling Form Controls

13-  Grouping Form Elements

