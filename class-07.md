 # summery
 ## What's a Table?
 ##### A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results
 ### Basic Table Structure 
 - ``<table>``
 - ``<tr>``
 - ``<td>``
 - `` <th>`` 
 - ``<thead>`` ``<tbody>`` ``<tfooter>`` table headingLong Tables
 - ##### You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
 - ##### exampel for table 
 ![table](https://media.prod.mdn.mozit.cloud/attachments/2017/01/23/14583/5bad217718ecd469850752f2d97b1137/numbers-table.png)
 
 
## updating un object 
##### to ubdate the value for properties you have to write like : `` hotel.name ='park';``
##### to delet value from properties use : `` delete hotel.name;``
### CREATING OBJECTS USING CONSTRUCTOR SYNTAX
#### LITERAL NOTATION like : 
`` var hotel = {
name: 'Quay' ,
rooms: 40,
booked: 25,
checkAvailability: function() {
return this.rooms - this .booked;
}
} ``

#### OBJECT CONSTRUCTOR NOTATION like :
`` function Hotel(name, rooms, booked) {
this.name = name;
th is.rooms = rooms;
this.booked = booked;
this.checkAvailability = function()
return this.rooms - this.booked;
} ;
var quayHotel =new Hotel('Quay', 40 , 25);
var parkHotel =new Hotel('Park', 120, 77); ``

### WHAT ARE BUILT-IN OBJECTS? 
##### Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like toolkit for creating interactive web pages. 
![object](https://www.researchgate.net/profile/Henrique_Gaspar/publication/317624714/figure/fig10/AS:668885598605336@1536486162639/HTML-Document-Object-Model-DOM-three-of-objects.png)

#### GLOBAL OBJECTS: STRING O BJECT
##### Whenever you have a value that is a string, you can use the properties and methods of the String object on that value. This example stores the phrase "Home sweet home " in a variable
`` var saying = ' home sweet ' ; ``


##### JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
##### Arrays and objects can be used to create complex data sets (and both can contain the other)
##### Web browsers implement objects that represent both the browser window and the document loaded into the browser window







