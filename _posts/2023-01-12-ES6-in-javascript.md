---
Layout:
Title:  ES6 in javascript
date: 2023-01-12
Categories:
---

# Introduction
Today i learned about ES6 in javascript:

# Body
- 1. I learned how to use Arrow Functions to Write Concise Anonymous Functions (=>) . You can use arrow function syntax to write anonymous functions.

- 2. I learned how Write Arrow Functions with Parameters and If an arrow function has a single parameter, the parentheses enclosing the parameter may be omitted. It is also possible to pass more than one argument into an arrow function.

Example:const doubler = item => item * 2;

- 3. How to use the Rest Parameter with Function Parameters : You can create functions that take a variable number of arguments. These arguments are stored in an array that can be accessed later from inside the function.

Example : function howMany(...args) { return "You have passed " + args.length + " arguments."; } console.log(howMany(0, 1, 2)); console.log(howMany("string", null, [1, 2, 3], { }));
you need to check the args array and allows us to apply map(), filter() and reduce() on the parameters array.

- 4.I learned How to Destruct Assignment to Assign Variables from Arrays : One key difference between the spread operator and array destructuring is that the spread operator unpacks all contents of an array into a comma-separated list. Consequently, you cannot pick or choose which elements you want to assign to variables.

an example : const [a, b] = [1, 2, 3, 4, 5, 6]; console.log(a, b);
the console will display the values of a and b as 1, 2.

- 5.C How to Create a Module Scrip : which is easily to share code among JavaScript files. In order to take advantage of this functionality, you need to create a script in your HTML document with a type of module.

an example : script type="module" src="filename.js">
You can use the import and export features you will learn about in the upcoming challenges.

- 6.I learned how to use export to Share a Code Block : this file is called math_functions.js that contains several functions related to mathematical operations. One of them is stored in a variable, add, that takes in two numbers and returns their sum.

it's an eaxmaple how to export : export const add = (x, y) => { return x + y; }