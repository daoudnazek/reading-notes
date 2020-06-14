# Understanding the problem domain is the hardest part of programming 

Learning the problem Domain is the hardest thing in programming.

## Why problem domains are hard

Many problem domains are like a puzzle with blurry picture or no picture at all, so it is difficult to understand and look completly different depending on your view point.

## What can you do about it 

To make the programming easier , you have to do one of these two things:

- Make the problem domain easier.
- Get better at understanding the problem domain.


# What is an object ?

Objects group together set of variables and functions to create a model from the real life.

**Variable** becomes known as properities when it is a part of an object.
**Function** becomes known as method when it is a part of an object 

## Example of an object 

![Object Example](https://appdividend.com/wp-content/uploads/2019/03/Javascript-Objects-Tutorial-Example-Working-With-Objects-in-JS.png)

In the previous example :

* The obeject represent apps.
* The property Key (name) is Name and its value is Facebook.
* The method key (name) is getApp and its value is the function.
* This is used to indicate that its using the property name of this Object.
* We use var appName = apps.name to access the object property (name).
* we use var appGet = apps.getApp to access the object method (getApp).


# Document Object Model (DOM)

It is a set of rules, not a part of html or java script , used to specify how the web browser should create a model of html , and how javascript can access and update the content of the web page.

**DOM tree** : used to specify the way that the browser should structure the web page and it is made of objects.
**Application Programming Interface (API)** : User interfaces let humans interact with programs , and tell the browser to update what is shown to the user.

![DOM](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Document-Object-Model-DOM-1280x720.jpg)

## DOM tree 

* **The Document Node** 
* **Element Nodes** 
* **Attribute Nodes** 
* **Text Nodes** 

### How to access the DOM tree 

1- Locate the node the represents the element you want to work with.
2- use its text content, child elements , and attributes.

* GetElementById();
* querySelector();
* getElementsByClassName();
* getElementsByTagName();
* querySelectorAll();


