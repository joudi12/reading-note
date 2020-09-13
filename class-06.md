# summery
## WHAT IS AN OBJECT? 
#### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names
## accessing an object and dot notation 
#### you accessing the properties or methods of an object using dot nation.
#### you can also access properties using square brackets
#### example :
 `` var hote l = {
name: 'Quay',
rooms: 40,
booked : 25,
checkAvailability: function() {
return this.rooms - this.booked;
}
} ;
JAVASCRIPT
var el Name = document .getElementByld('hotelName');
elName.textContent =hotel .name;
var elRooms = document.getElementByid{'rooms');
elRooms.textContent = hotel .checkAvailability(); ``

## THE DOM TREE IS A MODEL OF A WEB PAGE 
#### As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 
![js](https://www.tutorialrepublic.com/lib/images/html-dom-illustration.png)
## WORKING WITH THE DOM TREE
- STEP 1: ACCESS THE ELEMENTS 
- STEP 2: WORK W ITH THOSE ELEMENTS 
### METHODS THAT RETURN A SINGLE ELEMENT NODE: 
`` getElementByld( ' id ') ``
`` querySel ector( 'css selector') ``
### METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):
`` getEl ementsByClassName( 'class ' ) ``
`` getEl ementsByTagName( 'tagName ') ``
`` querySelectorAll ( 'css select or')``
#### Whenever a DOM query can return more than one node, it will always return a Nadel i st.
#### From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques. 
#### An element node can contain multiple text nodes and child elements that are siblings of each other. 
#### Browsers offer tools for viewing the DOM tree . 
