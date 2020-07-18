# Domain Modeling

The process of creating conceptual model for specific problem, that verify the understanding of that problem.

**Tips to follow**

* Build self contained objects with the same attributes and behaviors.
* Use constructor function to model attributes.
* Use small method that do one job to model bahaviors.
* Use **new** keyword to create objects.
* Store the newly created objects in variables.
* Use the this keyword inside methods.


# Tables 

Used to represent complex information in a grid fromat , which is more than one axis.

table tag : used to create table.
tr tag : idicates table row.
td tag : idicates table data.
th tag : indicates table heading.
colspan tag : idicates how many columns or rows the cell should run across.

thead tag: the heading of the table. 
tbody tag: the body of the table.
tfoot tag: the footer of the table.

![Table](https://assets.hongkiat.com/uploads/html-table-building-30-beautiful-examples-and-useful-javascripts/table-jquery-snippets.jpg)


# Functions, Methods, and Objects

## Constructive Notation

Create new object using the keyword new.

**Example**

var car = new object(); , this will create a new object with the name car.
car.name = 'toyota'; .... property.
car.color = 'white' .... property.
car.accelerating = function (){
      return value,
}; .... method.


**This** keyword : usually refers to one object where in which the function operates.

**Arrays** : is a special type of objects, which the key for each value is the index.

## Built In Objects 

1- Browser object model.
2- Document object model.
3- Global javascript objects.

