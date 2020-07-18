# HTML and CSS 

## Text

* **Headings <h1>** : there is six levels of headings ( h1,h2,h3,h4,h5,h6 ) , h1 is used for the main heading, the rest is for subheadings.

* **Paragraph <p>** 

* **Bold <b> and Italic <i>**

* **Superscript <sup> and Subscript <sub>** : superscript is used for suffixes of dates , while subscript is used for chemical formula.

* **strong <strong> and emphasis <em>** : strong is used for important words and the element will be shown in bold , emphasis is used for emphasis that changes the meaning of a sentence and the element will be shown in italic.

## Introducing CSS 

**CSS** is used to style html elemetns by rules, it consists of two parts, selecter and declration.
Declaratin sits between two barckets has two parts, property and value.
![css](https://www.w3schools.com/css/selector.gif)

### How to write CSS : 

1- External CSS file : all the rules are written in external files linked to the html file.
2- Inernal CSS : all the rules are written inside the html file.
3- Inline CSS : the rule is written inside each element.

# Javascript

## Basic Java script instructions 

**what** is script ? 

Script is a series of instructions followed one by one , each instrucation called statement and it ends with semicolon.

**What** is a variable ?

Variable is used to store data values, and it will be able to change and be compared to other values.

### Variable Decleration 

It consists of two parts : variable keyword and variable name 

**Var userName;**  : var is the variable keyword and userName is the variable name.

### Data types 

* Numeric Data type : 15
* String Data type : ' String ' 
* Boolean Data type : True or false

### Arrays 

Arrays is used for combining list of values in one array.

Example : colors = ['white', 'black' , 'grey']; 

Each value in the array has index, the first value index is 0, the second is 1 and so on.

### Expression and Operators 

Expression : size = 5 * 6 * 7 

Operators : + , - , > , < , ++ , -- , %

## Decisions and Loops 

Some places the script has to make decision to detemine which line should be ran. and we use conditional statments such as if and switch. 
The expression will return a value and the conditional statment will make the decision.

### Comparison Operators 

* == , !== : it only compares the values.
* === , !== : it compares both values and data type. 
* < , > , >= , <= .

### Logical Operators 

&& : Logical And
|| : Logical Or 
! : Logical Not 

### If statment : 

if ( x>=5 ) {
    do something;
}