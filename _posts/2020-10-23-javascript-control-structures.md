---
layout: post
title: JavaScript basics
categories: [JavaScript, Coding, Basics, Control Structures]
---

## Basic control structures in JS

### If statement

If statement is the most basic control structure usually available in any programming language.
If the statement in `()` is true then code inside the curly braces gets executed.

Examples:

```javascript
if (true) {
  console.log("this will always print");
}

if (false) {
  console.log("this will never print");
}
```

### If else statement

If the statement in `()` is true then code inside the curly braces gets executed,
otherwise the code inside the curly braces after *else* gets executed.

```javascript
if (true) {
  console.log("this will always print");
} else {
  console.log("this will never print");  
}

if (false) {
  console.log("this will never print");
} else {
  console.log("this will always print");
}
```

### Else if statement

If the statement in `()` is true then code inside the curly braces gets executed,
otherwise next block is checked and if it is false then the next one gets checked etc etc.

```javascript
if (true) {
  console.log("this will always print");
} else if (false) {
  console.log("this will never print");  
}

if (false) {
  console.log("this will never print");
} else if (true) {
  console.log("this will always print");
}

if (false) {
  console.log("this will never print");
} else if (false) {
  console.log("this will always print");
} else if (true) {
  console.log("this will always print");
}
```

### Switch

Switch is pretty similar to else if.

```javascript
switch ("John Doe") {
  case "Mary":
    console.log("Hello Mary!");
    break;
  case "Joe":
    console.log("Hello Joe!");
    break;
  case "John Doe":
    console.log("Hello John Doe!");
    break;
  default:
    console.log("Hello no name!");
    break;
}
```

## A bit more advanced example

Let's say that we have three variables:

```javascript
const name = "John Doe";
const sex = "Male";
const age = 45;
```

Let's write a short script to greet this user.

```javascript
if (sex === "Male") {
  console.log("Hello sir");
} else {
  console.log("Hello madam");
}

console.log("Your name is " + name);


if (age < 18) {
  console.log("You appear to be under 18");
} else if (age > 18 && age < 40) {
  console.log("You are over 18 years old but under 40 years");
} else {
  console.log("You are at least 40 years old");
}
```

In the next post we are going to take a look at different kinds of loops in JavaScript.
