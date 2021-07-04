# java script 
Today we learned the Js language . 
![javascript](https://2.bp.blogspot.com/-hUHZB4lkOfo/VWCGfzGBaFI/AAAAAAAACyI/Keb3hV6cm_M/s1600/JavaScript%2Bthe%2BRight%2BWay%2B-%2BFree%2Bbook%2BOnline.png)

This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more .
A complete and detailed list of operators and expressions is also available in the reference.

## Operators
JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

* Assignment operators
* Comparison operators
* Arithmetic operators
* Bitwise operators
* Logical operators
* String operators
* Conditional (ternary) operator
* Comma operator
* Unary operators
* Relational operators

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator . 
![java](https://4.bp.blogspot.com/-PQHNOWFNS9o/XAkNsyPerCI/AAAAAAAALks/ONXxkKH3lRwskA3cfiqPa-cGKlt8u-l6wCLcBGAs/s1600/javascript.jpg)

### functions 
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

Defining functions
Function declarations
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

* The name of the function.
* A list of parameters to the function, enclosed in parentheses and separated by commas.
* The JavaScript statements that define the function, enclosed in curly brackets, {...}.
function square(number) {
  return number * number;
}

#### Control flow
The control flow is the order in which the computer executes statements in a script.
Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 
For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

if (field==empty) {
    promptUser();
} else {
    submitForm();
}

##### functions 
A JavaScript function is a block of code designed to perform a particular task.
A JavaScript function is executed when "something" invokes it (calls it).
Example
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
![function](https://cdn.programiz.com/cdn/farfuture/oAZVf3IqOKOYj_aJ-IoYQvbJ2CB-B3y4HXSLXBUmYcY/mtime:1591592163/sites/tutorial2program/files/javascript-function-with-parameter.png)

###### operators 
Example
Assign values to variables and add them together:

let x = 5;         // assign the value 5 to x
let y = 2;         // assign the value 2 to y
let z = x + y;     // assign the value 7 to z (5 + 2)
![operator](https://i.ytimg.com/vi/wFB-ywsNPwg/maxresdefault.jpg)
