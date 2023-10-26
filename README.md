# timusweek1
Timus Full Stack Bootcamp Homework 1

1)History of JavaScript

The history of JavaScript is a fascinating journey in the world of web development. It began in 1995 when Brendan Eich developed it while working at Netscape Communications Corporation. JavaScript's first version was introduced in Netscape Navigator 2.0 in 1996, originally named LiveScript before being renamed JavaScript. In 1997, the ECMAScript standardization process began, shaping the language's evolution. Key milestones include ECMAScript 3 in 1999, which laid the foundation for modern JavaScript, and ECMAScript 5 in 2009, bringing significant language enhancements. The game-changing release came in 2015 with ECMAScript 2015 (ES6), introducing modern features like classes, arrow functions, and modules. JavaScript remains a continuously evolving language with ECMAScript 2022 and future versions driving its development. Today, JavaScript is a fundamental tool in web development and is widely used not only in web browsers but also on the server side, making it one of the most popular programming languages.

2)Data Types

JavaScript data types are typically categorized into two main groups: "primitive" and "object." Here's a list of JavaScript data types belonging to these two categories:

Primitive Data Types:
String,
Number,
Boolean,
Undefined,
Null,
Symbol

Object Data Types:
Object,
Array,
Function,
Date,
Other user-defined objects


3)Var,Let and Const

var, let, and const are keywords used to declare variables in the JavaScript language. While var is an older way to declare variables, with a limited scope known as function scope, let and const were introduced with ES6 (ECMAScript 2015) and have a block scope, meaning they are accessible and modifiable only within the block in which they are defined. Variables declared with let can have the same name in different scopes, while const is used for declaring constants where the value, once assigned, cannot be changed,this mean const is immutable. let and const are preferred in modern JavaScript applications as they contribute to writing safer and more predictable code.

4)JavaScript Array Methods

-Section 1. Array properties

length property – show you how to use the length property of an array effectively.


-Section 2. Adding / removing elements

push() – add one or more elements to the end of an array.

unshift() – add one or more elements to the beginning of an array.

pop() – remove an element from the end of an array.

shift() – remove the first element from an array.

splice() – manipulate elements in an array such as deleting, inserting, and replacing elements.
{Array.splice(position,num);}

slice() – copy elements of an array.{slice(start, stop);}


-Section 3. Finding elements

indexOf() – locate an element in an array.{Array.indexOf(searchElement, fromIndex)}

includes() – check if an element is in an array.

find() – find an element in an array

findIndex() – find the index of an element in an array.


-Section 4. High-order methods

map() – transform array elements.

filter() – filter elements in an array

reduce() – reduce elements of an array to a value.

every() – check if every element in an array passes a test.

some() – check if at least one element in an array passed a test.

sort() – sort elements in an array.

forEach() – loop through array elements.


-Section 5. Manipulating Arrays

concat() – merge two arrays into an array.


-Section 6. Creating Arrays

of() – improve array creation.

from() – create arrays from array-like or iterable objects.


-Section 7. Flattening arrays

flat() – flatten an array recursively up to a specified depth.

flatMap() – execute a mapping function on every element and flatten the result.


-Section 8. Arrays to Strings

join() – concatenate all elements of an array into a string separated by a seperator.


-Section 9. Advanced Operations

Destructuring – show you how to assign the elements of an array to variables.

Spread operator – learn how to use the spread operator effectively.


-Section 10. Accesing elements

at() – access array elements using both positive and negative indexes.


-Section 11. Multidimensional Array

Multidimensional Array – learn how to work with multidimensional arrays in JavaScript.


5)Do/Do While Difference

The difference between "do" and "do-while" loops represents how they control the repetition of a code block in a program. The "do" loop executes the code block at least once before checking the condition, while the "do-while" loop checks the condition after executing the code, ensuring that the code block is executed at least once. This distinction impacts their usage based on functional requirements and program needs.


6)For/For-Each Differnce

The fundamental difference between "for" and "for-each" loops lies in their methods for processing elements. The "for" loop is index-based and is used for iterating over a specific range or a specified number of times. The "for-each" loop, on the other hand, is used for directly processing elements and doesn't require index usage. Therefore, the "for" loop is preferred for operations that require index-based processing, while the "for-each" loop is more convenient for traversing and processing elements directly, especially in arrays and collections.
