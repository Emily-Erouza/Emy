---
Layout:
Title: Debugging
date: 2023-01-18
Categories:
---

# Introduction
- Today i learned about Debugging

# Body
- I learned about the following concept :

- 1.Catch Unclosed Parentheses, Brackets, Braces and Quotes : syntax error to be aware of is that all opening parentheses, brackets, curly braces, and quotes have a closing pair. Forgetting a piece tends to happen when you're editing existing code and inserting items with one of the pair types.

Also, take care when nesting code blocks into others, such as adding a callback function as an argument to a method.
- 2.Use of Assignment Operator Instead of Equality Operator : Branching programs, i.e. ones that do different things if certain conditions are met, rely on if, else if, and else statements in JavaScript

The assignment operator (=) in JavaScript assigns a value to a variable name. And the == and === operators check for equality (the triple === tests for strict equality, meaning both value and type are the same).
- 3.Catch Off By One Errors When Using Indexing : If you try to access an index equal to the length, the program may throw an "index out of range" reference error or print undefined. JavaScript indexing starts at zero, not one, which means the last index is always one less than the length of the item. I

- 4.Prevent Infinite Loops with a Valid Terminal Condition : Loops are great tools when you need your program to run a code block a certain number of times or until a condition is met, but they need a terminal condition that ends the looping.
  
  # Conclusion 
- an example of an infinite loop : function loopy() { while(true) { console.log("Hello, world!"); } }
it had no terminal condition to break out of the while loop inside loopy(). Do NOT call this function!