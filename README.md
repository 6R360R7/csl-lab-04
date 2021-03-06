# CSL Lab 04 - Arrays & Loops

## Overview:
In this learning activity we will explore Javascript arrays and loops, learn what they are and how to use them.



## Objectives:
* How to create arrays to store a sequence of values in one variable.
* How to access or change elements of an array using “bracket notation”.
* How to add elements to an array using the push() method.
* How to iterate through an array using a for loop.


## Array:
**The Array object is used to store multiple values in a single variable:**
```javascript
var fruit = ["Apple", "Orange", "Banana"];
```
## Loops:
Loops are handy, if you want to run the same code over and over again, each time with a different value.
Different Kinds of Loops
## Types of Loops:
* for - loops through a block of code a number of times
* for/in - loops through the properties of an object
* for/of - loops through the values of an iterable object
* while - loops through a block of code while a specified condition is true
* do/while - also loops through a block of code while a specified condition is true
## The For Loop:
**The for loop has the following syntax:**
```javascript
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
* **Statement 1:** is executed (one time) before the execution of the code block.
* **Statement 2:** defines the condition for executing the code block.
* **Statement 3:** is executed (every time) after the code block has been executed.
### For Loop Example (p5js):
```javascript
for (i = 0; i < 5; i++) {
  console.log("The number is " + i);
}
```

***

## Lab Project 1: Define and Log Items In Array
Open in p5js editor: [csl-04-01](https://editor.p5js.org/grgry13/sketches/6AwK0KE1t)

**Pseudocode:**
 1. Define dataset 
 1. Add values to dataset 
 1. Log dataset values sequentially 

```javascript
// Define dataset

var fruit = [];


function setup() { 
  createCanvas(400, 400);
  background(220);
  // Assign values to dataset 
  fruit = ['Apple', 'Orange', 'Banana'];
  console.log(fruit);

  // Log dataset values sequentially.
  for (var i = 0; i < 3; i++) {
    console.log(fruit[i]);
  }
}

function draw() {}
```

## Lab Project 2:  Array Manipulation Exploration
Open in p5js editor: [csl-04-02](https://editor.p5js.org/grgry13/sketches/URP_HxJ11)

Here we will explore this code from The Coding Train to see arrays and array editing in action.
We will also touch on the concept of opjects in regards to computer programming.

## Debreifing 
During the past 4 labs we explored some basic fundimental concepts behind writing code.

* [Functions & Arguments](https://www.w3schools.com/js/js_functions.asp)
* [Variables](https://www.w3schools.com/js/js_variables.asp)
* [Arrays](https://www.w3schools.com/js/js_arrays.asp)
* [Loops](https://www.w3schools.com/js/js_loop_for.asp)

We also wrote some programs to solidify understanding.
* [Lab 01](https://editor.p5js.org/grgry13/sketches/LIX_GL9xD)
* [Lab 02](https://editor.p5js.org/grgry13/sketches/5NWhkjIHo)
* [Lab 03](https://editor.p5js.org/grgry13/sketches/uBCYm5SPg)
* [Lab 03 02](https://editor.p5js.org/grgry13/sketches/uBCYm5SPg)
* [Lab 04 01](https://editor.p5js.org/grgry13/sketches/yKucLB22R)
* [Lab 04 02](https://editor.p5js.org/grgry13/sketches/URP_HxJ11)

I hope you take what we explored and continue to learn more about writing code. :)
Below I added a few links to some great places to start. 


## Resources
* [Beginner](https://thecodingtrain.com/beginners/p5js/)
* [Intermediate - The Nature of Code](https://thecodingtrain.com/learning/nature-of-code/)
* [Advanced p5js](https://thecodingtrain.com/learning/nature-of-code/)
