# 301 - Read02

## jQuery 

**jQuery** offers a simple way to preform javascript tasks quickly in all browsers without problems.It is a JavaScript file that we include in our web pages.

- Select Elements : $('li')
- Perform Tasks : $('li').addClass('Good')
- Handle Events

### Why To Use jQuery 

jQuery doesn`t anything more than what we can do with pure JavaScript, It is just simpler and makes code more readable.

1- Simple Selectors.
2- Common tasks in less code.

![jQuery Vs Pure JavaScript](https://isabelcastillo.com/wp-content/uploads/javascript-table-jquery-600x226.png)


**Example of jQuery** 

$(document).ready(function(){
  $("p").click(function(){
    $(this).hide();
  });
});