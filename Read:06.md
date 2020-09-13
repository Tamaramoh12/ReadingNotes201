## What is object?

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. 

In an object, variables and functions take on new names. (variables become properties, Functions become methods).
 
Properties tell us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms. 
 
Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms. 
 
**How to declare an object?** 
 
The object is in curly braces. It is stored in a variable.

Like: var ObjName = {}

properties and methods have a name and a value. In an object, the name is called a key
 
An object cannot have two keys with the same name. This is because keys are used to access their corresponding values. 
 
The value of a property can be a string, number, Boolean, array, or even another object. 

The value of a method is always a function. 

Example:

var hotel = {    //object decalration

name: 'Quay',    /* the properties (variables)

rooms: 40,       .................

booked: 25,      .................

gym: true,       ................

roomTypes: ['twin', 'double', 'suit],       */

checkAvailability: function() {      //method (function)

return this.room - this.booked;

}

};    //close the object


**How to access an object?** 

we can access the properties or methods using dot notation, In addition we can access properties using square brackets.

Ex:  var hotelNam = hotel.name;
     var roomsfree.checkAvailability();
     
Ex: var hotelName = hotel['name'];



