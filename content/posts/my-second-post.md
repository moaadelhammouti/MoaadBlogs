---
title: "Let's talk about React :"
date: 2021-01-21T17:03:50+01:00
draft: true
---
React :
first of all react is a javaScript library, so for you to understand React you must know 7 essential concepts that you should know about JavaScript to master React.

1 - Function declaration and Arrow functions :
-JavaScript functions and classes
but unlike JavaScript functions,React components return JSX elements that are used to structure our application interface.
JavaScript functions are named in camel casing, while React function components are written with pascal casing(in which all words are capitalized).

there are two ways to write a function in JavaScript : using the function(a function declaration), and as an arrow function.

One small benefit of using function declarations over arrow functions is that you don't have to worry about problems with hoisting.
Another small difference in using the function declaration syntax is that you can immediately export a component from a file using export default or export before the function is declared. You can only use the export keyword before arrow functions (default exports must be placed on a line below the component).

2. Template Literals ` ` :

before ES6 JavaScript to add strings together you need to use +.
With the addition of ES6, we were given a newer form of string called a template literal, which consists of two back ticks `` instead of single or double quotes.

Instead of having to use the + operator, we can connect strings by putting a JavaScript expression (such as a variable) within a special ${} 

3. Short Conditionals: &&, ||, Ternary Operator:
The ternary operator functions exactly the same as an if-statement, but it is shorter, it is an expression (not a statement), and can be inserted within JSX

the && (and) operator
the || (or) operator.

4. Three Array Methods: .map(), .filter(), .reduce()

What if we have an array and we want to iterate over that array to show each array element within an individual JSX element?
For this, we can use the .map() method. It allows us to transform each element in our array in the way we specify with the inner function.
Note that this isn't exactly the same as the normal JavaScript .map() method, but is very similar. */

.filter(), as its name indicates, allows us to filter certain elements out of our array. For example, if we wanted to remove all names of programmers that started with "J", we could do so with .filter()

the .reduce() array method, which is capable of transforming array values into virtually any data type, even non-array values.
Here's .reduce() performing the same operation as our .filter() method above:

5. Object Tricks: Property Shorthand, Destructuring, Spread Operator

What is great about the object spread is that you can spread in as many objects into a new one as you like, and you can order them like properties.

6: Promises + Async/Await Syntax
Promises traditionally use callbacks to resolve our asynchronous code. We use the .then() callback to resolve successfully resolved promises, while we use the .catch() callback to resolve promises that respond with an error.
Instead of always needing to use callbacks to resolve our data from a promise, we can use a cleaned syntax that looks identical to synchronous code, called the async/await syntax.

To use them, we need to make sure our asynchronous code is in a function prepended with the keyword async. Any promise's value can then be resolved by placing the keyword await before it.

7. ES Modules + Import / Export syntax
ES6 gave us the ability to easily share code between our own JavaScript files as well as third-party libraries using ES modules.
As far as JavaScript code goes, we can import and export variables and functions. There are two ways of importing and exporting, as named imports/exports and as default imports/exports.
