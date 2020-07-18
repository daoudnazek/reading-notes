![JS Debugging](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing-640x480.png)

# JS Debugging

It is the process of finding the errors in the script and fix it.

The JavaScript interpreter uses the concept of execution contexts.
- One global excution context (the main that is outside any function).
- each function created its own excution context.

* **The Stack** 

Java script process one line of code at a time, when statment needs a data from a function , it stacks the new function on top of the current task.

1- **Prepare** : 
 - new scope is created.
 - variable , functions are created.
 - the value of the keyword is determined.

2- **Execute** :
 - execute statments.
 - assign values to the variable.
 - run functions code.

## Error Objects:
 
There are seven types of object errors :

* **Error** 
* **SyntaxError**
* **ReferenceError** 
* **TypeError**
* **RangeError**
* **UrlError**
* **EvalError**

And there properitits can be :

* name 
* message
* fileNumber 
* lineNumber


## How to handle errors 

1- Debug the script to fix errors 
2- Handle errors gracefully (using **try catch**)

## How to debug 

- Where is the problem.
- What is the problem.

**Javascript console** will tell you when there is a problem, where is it, and what the issue it seems to be.

### Console Methods 

- console.log() : to get values in the console.
- console.info(): to get general information.
- console.warn(): used for warnings.
- console.error(): used to hold errors.

### Breakpoints

Used to pause the execution of the code on any line , to check the values at that point.

### try , catch , finally 

**try** : try to excute this code.
**catch** : if there is an exception run this code. 
**finally** : always gets excuted.
