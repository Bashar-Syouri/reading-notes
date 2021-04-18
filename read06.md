# Welcome :)

![function](https://i.ytimg.com/vi/QX3kGsfGqz8/maxresdefault.jpg)

## WHAT IS A FUNCTION?


**Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).**






**Declaring functions**

To declare a function, you use the function keyword, followed by the function name, a list of parameters, and the function body as follows:

function functionName(parameters) {
   Gunction body
    
}
###### Code language: JavaScript (javascript)

The function name must be a valid JavaScript identifier. By convention, the function name should start with a verb like getData(), fetchContents( ), or isValid( ).

A function can accept zero, one, or multiple parameters. If there are multiple parameters, you need to separate them by commas (,).

The following declares a function named say() that accepts no parameter:

function say() {
  
}
###### Code language: JavaScript (javascript)


The following declares a function named square() that accepts one parameter:

function square(a) {
  

}
###### Code language: JavaScript (javascript)


And the following declares a function named add() that accepts two parameters:

function add(a, b) {
  
}
Code language: JavaScript (javascript)


Inside the function body, you can implement the logic. For example, the following say() function simply shows a message to the console:

function say(message) {
  
  console . log( message );
}
Code language: JavaScript (javascript)


In the body of the say() function, we call the console.log() function to output a message to the console.
