---
Layout:
Title:  Functional Programming in JS.
date: 2023-02-06
Categories:
---

# Introduction
- Today I learned about Functional Programming in JS.
- Learn About Functional Programming : Functional programming is a style of programming where solutions are simple, isolated functions, without any side effects outside of the function scope: INPUT -> PROCESS -> OUTPUT
# Body
- ## Functional programming is about :
- 1.Isolated functions - there is no dependence on the state of the program, which includes global variables that are subject to change
- 2.Pure functions - the same input always gives the same output
- 3.Functions with limited side effects - any changes, or mutations, to the state of the program outside the function are carefully controlled
- Understand Functional Programming Terminology : The FCC Team had a mood swing and now wants two types of tea: green tea and black tea. General Fact.

# Conclusion
- ## functional terminology:
- Callbacks are the functions that are slipped or passed into another function to decide the invocation of that function. You may have seen them passed to other methods, for example in filter, the callback function tells JavaScript the criteria for how to filter an array.
First class functions functions that can be assigned to a variable, passed into another function, or returned from another function just like any other normal value
Higher order functions functions that take a function as an argument, or return a function as a return value
A lambda when functions are passed in to or returned from another function, then those functions which were passed in or returned can be called a lambda.
- Avoid Mutations and Side Effects Using Functional Programming : in functional programming, changing or altering things is called mutation, and the outcome is called a side effect. A function, ideally, should be a pure function, meaning that it does not cause any side effects.

- To Avoid External Dependence in a Function : Another principle of functional programming is to always declare your dependencies explicitly. This means if a function depends on a variable or object being present, then pass that variable or object directly into the function as an argument.