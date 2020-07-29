# 301 - Read09

## Functional Programming 

What is fumctional programming ? 

It is a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

**Pure Functions** 

- return the same result if given the same argument.
- don`t cause side effects .

*Not Pure Function Example* :

let PI = 3.14;

const calculateArea = (radius) => radius * radius * PI;

calculateArea(10); // returns 314.0

Change to Pure Function 

*Pure Function Example* :

let PI = 3.14;

const calculateArea = (radius, pi) => radius * radius * pi;

calculateArea(10, PI); // returns 314.0


- Reading Files : is not a pure function 
- generating random numbers : is not a pure function 


When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.


## Refactoring 

It's important to get your code right the first time because in many businesses there isn't much value in refactoring.

**Strategies** to implement methods that can lead to easier to read the code 

- Return early from functions.

- Cache variables so functions can be read like sentences.

- Check for Web APIs before implementing your own functionality.