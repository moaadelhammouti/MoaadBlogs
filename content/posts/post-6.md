---
title: "What's the difference between console. dir and console.log ?"
date: 2021-02-22T09:43:30+01:00
draft: true
---

What's the difference between console. dir and console.log ?

Console Object: The Console object provides access to the browser’s debugging console, which can be seen using F12 or ctrl+shift+j. Console object contains many methods, log() and dir() are the most used.
The console.log() method prints out a toString representation of the object in the console to the user.
Syntax:
console.log(object) or console.log("string", object)
The console. dir() method output the list of object properties of a specified object in the console to the user.
Syntax:
console.dir(object)
In simple words, the console.log() returns the object in its string representation and console.dir() recognizes the object just as an object and outputs its properties. Both log() and dir() return the string just as a string.
