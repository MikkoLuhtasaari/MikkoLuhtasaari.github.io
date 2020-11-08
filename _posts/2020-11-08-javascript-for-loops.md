---
layout: post
title: JavaScript for loops
categories: [JavaScript, Coding, Basics, Control Structures]
---

In the last post we went through if-statements.
This time we are going to look at for-loops.
With these loops you can execute code multiple times.

## For-loop structure

For-loop is the most common way to execute some code multiple times.
If you wanted to print out `Hello World` multiple times you could create a loop rather
than copy and paste the same statement multiple times.

Let's go ahead and create our first for-loop.

```javascript
for (let i = 0; i < 3; i++) {
  console.log("Hello World");
}
// Hello World
// Hello World
// Hello World
```

We can break down the for-loop to four different parts.

* Initializing the variable
  * `let i = 0;` we introduce a variable `i` with value of `0`
* Introducing the exit condition
  * `i < 3;` we tell the JS engine that this should be ran while `i` is less than `3`
* What should change after each loop
  * `i++` we increment the value of `i` by one after each loop
* What code should be executed for each loop
  * We tell what code to execute inside the curly braces

## Common use cases

Most commonly for-loop is used to iterate over an array.
Let's introduce an array and print out the contents.

```javascript
const words = ["Hi", "my", "name", "is", "Mikko"];

for (let i = 0; i < words.length; i++) {
  console.log(words[i]);
}
// Hi
// my
// name
// is
// Mikko
```

In `i < words.length;` we define that the loop must be ran while the `i` is less
than the length of the array.
We can access the value of the `words` array with `words[i]`.

## For of

Another way of iterating over an array is for..of.

Let's use the same `words` array and iterate over it by using for..of.

```javascript
const words = ["Hi", "my", "name", "is", "Mikko"];

for (const word of words) {
  console.log(word);
}
// Hi
// my
// name
// is
// Mikko
```

This allows us to use a slightly simpler syntax that is faster to write and easier to read.
It can also be used to iterate over a string.

```javascript
const word = "Hello";

for (const letter of word) {
  console.log(letter);
}
// H
// e
// l
// l
// o
```
