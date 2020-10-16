---
layout: post
title: JavaScript basics
categories: [JavaScript, Coding, Basics]
---

## Introduction to JavaScript

*JavaScript* (also known as *JS*) is **THE** programming language of the web.
To get started you don't even have to install anything.
JavaScript is already running in the browser that you are using to read this page!

### What is JavaScript

We are not going to go too deep into what JavaScript actually is.
This is going to be a quick overview of the language.

JavaScript was developed to look like [Java](https://www.java.com/en/) and
also the name was supposed to make it appeal to Java developers.
But that is about how much these two languages have in common.
Java is a class based programming language, whereas JS is prototype based language.
Even though newer JS versions have *classes* they are simply syntactic sugar on top of prototypes.

JS supports many programming paradigms including *event-driven*, *imperative* and *functional(ish)*.
Imperative programming paradigm is what people are the most familiar with.
In this blog you are not going to find that much imperative programming.
We are going to focus on event-driven and functional JS.

## Getting started with JavaScript

### Variable types



### Most common data and structure types

* String

```javascript
const string = "Hello World!";
console.log(typeof string); // string
```

* Boolean

```javascript
const boolean = true;
console.log(typeof boolean); // boolean
```

* Number

```javascript
const number = 42;
console.log(typeof number); // number
```

* undefined

```javascript
let variable;
console.log(typeof variable); // undefined
```

* Array

```javascript
const array = [];
console.log(typeof array); // object
console.log(Array.isArray(array)); // true
```

* Object

```javascript
const object = {};
console.log(typeof object); // object
```
