---
Layout:
Title: Object Oriented Programming in JS.
date: 2023-02-03
Categories:
---

# Introduction
- Today i learned about Object Oriented Programming in JS.

# Body
- 1.Use Inheritance So You Don't Repeat Yourself : There's a principle in programming called Don't Repeat Yourself (DRY). The reason repeated code is a problem is because any change requires fixing code in multiple places. This usually means more work for programmers and more room for errors.

- 2.Inherit Behaviors from a Supertype : you created a supertype called Animal that defined behaviors shared by all animals:

an example : let animal = new Animal()
This challenge covers the first step: make an instance of the supertype (or parent). You already know one way to create an instance of Animal using the new operator:
let animal = Object.create(Animal.prototype);
Object.create(obj) creates a new object, and sets obj as the new object's prototype. Recall that the prototype is like the "recipe" for creating an object. By setting the prototype of animal to be the prototype of Animal, you are effectively giving the animal instance the same "recipe" as any other instance of Animal.
animal.eat(); animal instanceof Animal;
The instanceof method here would return true.

- 3.Reset an Inherited Constructor Property : When an object inherits its prototype from another object, it also inherits the supertype's constructor property.

Here's an example: function Bird() { } Bird.prototype = Object.create(Animal.prototype); let duck = new Bird(); duck.constructor

# Conclusion
- Understand the Immediately Invoked Function Expression (IIFE) : A common pattern in JavaScript is to execute a function as soon as it is declared:

(function () { console.log("Chirp, chirp!"); })();
- This is an anonymous function expression that executes right away, and outputs Chirp, chirp! immediately.
I learned hoe to use an IIFE to Create a Module.