---
Layout:
Title: Generate random whole numbers , ParseInt function , Ternary operator and How to use recursion in javascript.
date: 2023-01-11
Categories:
---
# Introduction
 - Today I learned about Generate random whole numbers , ParseInt function , Ternary operator and How to use recursion in javascript.
 
 # Body
- Generate Random Fractions with JavaScript : it has a Math.random() function that generates a random decimal number between 0 (inclusive) and 1 (exclusive).Therefore Math.random() can return a 0 but never return a 1.

- 2.Generate Random Whole Numbers with JavaScript : We use Math.random() to generate a random decimal. Multiply that random decimal by 20. Use another function, Math.floor() to round the number down to its nearest whole number.
this how the code look like : Math.floor(Math.random() * 20);

- 3.Generate Random Whole Numbers within a Range : we can generate a random whole number that falls within a range of two specific numbers. To do this, we'll define a minimum number min and a maximum number max.
This is how the code look like : Math.floor(Math.random() * (max - min + 1)) + min

- 4.The parseInt () Function : is a parses string and returns an integer.
an example of parseInt function : const a = parseInt("007");

- 5.The parseInt() Function with a Radix : the parseInt() function parses a string and returns an integer. It takes a second argument for the radix, which specifies the base of the number in the string. The radix can be an integer between 2 and 36.
The function call looks like: parseInt(string, radix);

- 6.The Conditional (Ternary) Operator : the conditional operator, also called the ternary operator, can be used as a one line if-else expression.

The syntax is a ? b : c, where a is the condition, b is the code to run when the condition returns true, and c is the code to run when the condition returns false.
- 7.Use Multiple Conditional (Ternary) Operators : you can chain them together to check for multiple conditions. The following function uses if, else if, and else statements to check multiple conditions.
for example : function findGreaterOrEqual(a, b) { return (a === b) ? "a and b are equal" : (a > b) ? "a is greater" : "b is greater"; }

- 8.Use Recursion to Create a Countdown : a recursive function returns an array containing the numbers 1 through n. This function will need to accept an argument, n, representing the final number.
 
 # conclusion
an example : [1, 2, ..., n - 1].
9.Use Recursion to Create a Range of Numbers : we defined a function named rangeOfNumbers with two parameters.