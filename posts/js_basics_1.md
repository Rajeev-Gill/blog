---
title: Javascript Basics Part 1
description: This is a post on My Blog about basic Javascript methods.
date: 2022-06-03
tags:
  - Tech
  - Javascript
layout: layouts/post.njk
---

## Cool console methods
```js
console.table({a:1, b:1})
console.error("Something went wrong")
console.warn("Something went loopy")

console.time("timer");
console.table({a:1, b:1})
console.error("Something went wrong")
console.warn("Something went loopy")
console.timeEnd("timer");
```

## var,let,const
```js
//initiate var without empty string
var something;

//initiate let and assign value '5'
let val;
val = 5;

//initiate a 'constant' (unchangeable) variable
const unchangeable = "unchangeable";

//intiate a constant object
const person = {
    name: "jeev",
    age: "22"
}
```