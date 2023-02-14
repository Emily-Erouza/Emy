---
Layout:
Title:  Functional Programming in JS.
date: 2023-02-07
Categories:
---

# Introduction
- Today i learned about Functional Programming in JS:

# Body
- a.Return Part of an Array Using the slice Method : The slice method returns a copy of certain elements of an array.The slice method does not mutate the original array, but returns a new one.

Here's an example : const arr = ["Cat", "Dog", "Tiger", "Zebra"];
const newArray = arr.slice(1, 3);
newArray would have the value ["Dog", "Tiger"].

- b.Combine Two Arrays Using the concat Method : Concatenation means to join items end to end.the method is called on one, then another array is provided as the argument to concat, which is added to the end of the first array. It returns a new array and does not mutate either of the original arrays.

Here's an example : [1, 2, 3].concat([4, 5, 6]);
The returned array would be [1, 2, 3, 4, 5, 6].

- c.Use the reduce Method to Analyze Data : The reduce method allows for more general forms of array processing, and it's possible to show that both filter and map can be derived as special applications of reduce. The callback function accepts four arguments.The first argument is known as the accumulator, which gets assigned the return value of the callback function from the previous iteration, the second is the current element being processed, the third is the index of that element and the fourth is the array upon which reduce is called.

- d.Sort an Array Alphabetically using the sort Method : The sort method sorts the elements of an array according to the callback function.

For example:
function ascendingOrder(arr) {
return arr.sort(function(a, b) { return a - b; }); }