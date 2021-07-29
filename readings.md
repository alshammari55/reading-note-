# html lists 

There are lots of occasions when we 
need to use lists. HTML provides us with 
three different types:
● Ordered lists are lists where each item in the list is 
numbered. For example, the list might be a set of steps for 
a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section 
number.
● Unordered lists are lists that begin with a bullet point 
(rather than characters that indicate order).
● Definition lists are made up of a set of terms along with the 
definitions for each of those terms.


<ol>
The ordered list is created with 
the <ol> element.
<li>
Each item in the list is placed 
between an opening <li> tag 
and a closing </li> tag. (The li
stands for list item.)
  
<ul>
The unordered list is created 
with the <ul> element.
<li>
Each item in the list is placed 
between an opening <li> tag 
and a closing </li> tag. (The li
stands for list item.)

  
CSS 
  
At the beginning of this section on CSS, 
you saw how CSS treats each HTML 
element as if it lives in its own box.
You can set several properties that affect the appearance of 
these boxes. In this chapter you will see how to:
● Control the dimensions of your boxes
● Create borders around boxes
● Set margins and padding for boxes
● Show and hide boxes
Once you have learned how to control the appearance of each 
box, you will see how to position these boxes on your pages in 
Chapter 15 when we look at page layout .

You can specify the color of a 
border using either RGB values, 
hex codes or CSS color names 
(as you saw on pages 251-252).
It is possible to individually 
control the colors of the borders 
on different sides of a box using:
border-top-color
border-right-color
border-bottom-color
border-left-color
It is also possible to use a 
shorthand to control all four 
border colors in the one 
property:
border-color: darkcyan 
deeppink darkcyan 
deeppink;
The values here appear in 
clockwise order: top, right, 
bottom, left.
  
ARRAYS  
  
An array is a special type of variable. It doesn't 
just store one value; it stores a list of values. 
You should consider using an 
array whenever you are working 
with a list or a set of values that 
are related to each other. 
Arrays are especially helpful 
when you do not know how 
many items a list will contain 
because, when you create the 
array, you do not need to specify 
how many values it will hold. 
If you don't know how many 
items a list will contain, rather 
than creating enough variables 
for a long list (when you might 
only use a small percentage 
of them), using an array is 
considered a better solution. 
For example, an array can be 
suited to storing the individual 
items on a shopping list because 
it is a list of related items. 
Additionally, each time you write 
a new shopping list, the number 
of items on it may differ. 
As you will see on the next page, 
values in an array are separated 
by commas. 
In Chapter 12, you will see that 
arrays can be very helpful when 
representing complex data. 

EXPRESSIONS 
An expression evaluates into (results in) a single value. Broadly speaking 
there are two types of expressions. 
1 
EXPRESSIONS THAT JUST ASSIGN A 
VALUE TO A VARIABLE 
In order for a variable to be useful, it needs to be 
given a value. As you have seen, this is done using 
the assignment operator (the equals sign). 
var color = 'beige'; 
The value of co 1 or is now beige. 
When you first declare a variable using the var 
keyword, it is given a special value of undefined. 
This will change when you assign a value to it. 
Technically, undefined is a data type like a number, 
string, or Boolean. 
EXPRESSIONS THAT USE TWO OR 
MORE VALUES TO RETURN A 
SINGLE VALUE 
You can perform operations on any number of 
individual values (see next page) to determine a 
single value. For example: 
var area = 3 * 2; 
The value of area is now 6. 
Here the expression 3 * 2 evaluates into 6. This 
example also uses the assignment operator, so the 
result of the expression 3 * 2 is stored in the variable 
called area. 
Another example where an expression uses two 
values to yield a single value would be where two 
strings are joined to create a single string. 
  
USING IF ... ELSE 
STATEMENTS 
  
if ... e 1 se statement allows you 
to provide two sets of code: 
1. one set if the condition 
evaluates to true 
2. another set if the condition is 
false .
  
SWITCH STATEMENTS 

A switch statement starts with a 
variable called the switch value. 
Each case indicates a possible 
value for this variable and the 
code that should run if the 
variable matches that value.
  
  
  
  
 
