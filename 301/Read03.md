# 301 - Read03

## MUSTACHE 

**What** is JavaScript templating ?

Javascript templating is a fast and efficient technique to render HTML templates with Javascript by using a JSON data source. by either insert variables or run programming logic. the template engine will change the variable with actual value during runtime.

**What** is Mustach ?

It is a logic-less template syntax, which there is no if statements, else clauses, or for loops.Instead, there are only tags. Mustach.js is considered the base of JavaScript templating.

**Mustach Syntax** 

Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn


## Flexbox

It is a way to layout, align and distribute the items inside a container, even when their size is not known. The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space.


### Properties for the Parent (flex container)

![Flex Container](https://css-tricks.com/wp-content/uploads/2018/10/01-container.svg)

**display**
**flex-direction**
**flex-wrap**
**flex-flow**
**justify-content**
**align-items**
**align-content**

### Properties for the Children (flex items)

![Flex Children](https://css-tricks.com/wp-content/uploads/2018/10/02-items.svg)

**order**
**flex-grow**
**flex-shrink**
**flex-basis**
**flex**
**align-self**