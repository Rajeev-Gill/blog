---
title: Document Object Model (DOM) Basics Part 1
description: This is a post on My Blog about basic DOM methods.
date: 2022-06-03
tags:
  - Tech
  - Javascript
layout: layouts/post.njk
---

## The Window Methods, Objects and Properties
The window is the global object in client side js 
```js

alert("this is an alert");

const input = prompt();

console.log(input + "entered into prompt box");

//Confirm: This throws up a box where you have to either press okay or cancel
//Pressing okay returns true
//Pressing cancel probably returns false
if(confirm("Are you sure?")){
    console.log("Yes");
} else {
    console.log("no");
}

//Properties

let val;

//Outer height and width
val = window.outerHeight;
val = window.innerHeight; //Accounts for visible page area only

val = window.scrollY; //Returns the value of how many pixel from top user is scrolled scrollX for horizontal

//Location object
val = window.location;
val = window.location.search; //Returns query string parameters
```

## Redirect
```js
window.location.href = "https://google.com"; //Setting the url will redirect page to google
window.location.reload();
```

## History object - Access browser history
```js
window.history.go();
val = window.history.length;
```

## Navigator Object
```js
val = window.navigator;
val = window.navigator.vendor;
val = window.navigator.platform;

console.log(val);
```