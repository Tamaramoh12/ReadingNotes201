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


