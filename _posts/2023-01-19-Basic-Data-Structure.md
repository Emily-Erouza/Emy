---
Layout:
Title: Basic Data Structures in JS.
date: 2023-01-18
Categories:
---

# Introduction
 - Today i learned about Basic Data Structures in JS.

# Body
- a.Add Items to an Array with push() and unshift() : the push() method adds elements to the end of an array, and unshift() adds elements to the beginning.

- b.Remove Items from an Array with pop() and shift() : pop() removes an element from the end of an array, while shift() removes an element from the beginning. The key difference between pop() and shift() and their cousins push() and unshift(),

- c.Remove Items Using splice() : splice() allows us to do just that remove any number of consecutive elements from anywhere in an array.Arrays are zero-indexed , so to indicate the first element of an array, we would use 0. Splice()'s first parameter represents the index on the array from which to begin removing elements.

an example :let array = ['today', 'was', 'not', 'so', 'great']; array.splice(2, 2); Here we remove 2 elements, beginning with the third element (at index 2). array would have the value ['today', 'was', 'great'].
- d.Combine Arrays with the Spread Operator : Huge advantage of the spread operator is the ability to combine arrays, or to insert all the elements of one array into another, at any index.Using Spread syntax makes the following operation extremely simple.

an example : let thisArray = ['sage', 'rosemary', 'parsley', 'thyme'];
let thatArray = ['basil', 'cilantro', ...thisArray, 'coriander'];
thatArray would have the value ['basil', 'cilantro', 'sage', 'rosemary', 'parsley', 'thyme', 'coriander'].
- e.Check For The Presence of an Element With indexOf() : indexOf() takes an element as a parameter, and when called, it returns the position, or index, of that element, or -1 if the element does not exist on the array.