---
Layout:
Title: Object Oriented Programming
date: 2023-02-01
Categories:
---

# Introduction
Today i learned about Object Oriented Programming :

# Body
- a.Verify an Object's Constructor with instanceof : a constructor function creates a new object, that object is said to be an instance of its constructor.

- b.Use Prototype Properties to Reduce Duplicate Code : A better way is to use the prototype of Bird. Properties in the prototype are shared among ALL instances of Bird.

Here's how to add numLegs to the Bird prototype: Bird.prototype.numLegs = 2;
- c.Understand the Constructor Property

- d.Remember to Set the Constructor Property when Changing the Prototype : It erases the constructor property! This property can be used to check which constructor function created the instance, but since the property has been overwritten, it now gives false results.

An example : duck.constructor === Bird; duck.constructor === Object; duck instanceof Bird; In order, these expressions would evaluate to false, true, and true.
# Conclusion
Understand the Prototype Chaine : The hasOwnProperty method is defined in Object.prototype, which can be accessed by Bird.prototype, which can then be accessed by duck. In this prototype chain, Bird is the supertype for duck, while duck is the subtype. Object is a supertype for both Bird and duck. Object is a supertype for all objects in JavaScript. Therefore, any object can use the hasOwnProperty method.

This is an example of the prototype chain.
let duck = new Bird("Donald");
duck.hasOwnProperty("name");