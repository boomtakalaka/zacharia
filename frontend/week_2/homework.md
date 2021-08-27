# Homework

## Setup

Create a HTML page as needed. You can write all the JavaScript in a <script> tag in your page. Remember that you have to use 'window.onload' if you want to access DOM elements in your script.

## 'Pure' JavaScript

Given this array: ```const arr = [1, 'two', { three: null }, () => 'four']```

1) Using a `for` loop, print each element into the console
2) Using a `for` loop, filter by:
- Numbers
- Strings
- Objects
- Functions
3) Using a `for` loop, create a new array from the original array where in the new array every element is a string representation of the original element. Hint: The object can be stringified with `JSON.stringify`
4) Do all the above without using a `for` loop
5) Write a function which calls a function that is passed in as an argument to it 10 times.
6) Create an object literal with properties of your choosing
7) Add a property _after_ the creation of the above object and print it out

## 'Browser` JavaScript

Create a page with any elements with your choosing

1) Select an element by ID and change its background colour
2) Select an element by class and change its background colour
3) Select multiple elements by the same class and change all their background colours
4) Change the content of an element on click
5) Change the content of an element on click of a different element
6) Create an unordered list (`<ul>`) on click of an element. The list elements' content should come from an array in JavaScript
7) Same as 6, but clicking on an element deletes it from the list
8) Same as 7, but add an text input element and a button. When the button is pressed and there is text in the input element, add an element to the list with the text content of the input element.
9) Create an unordered list with some text in each <li> element. Each element should have a data attribute (name it data-name) that has the reversed text of the text in the element. Clicking on each element will set another element's (any element of your liking) text to the value of that attribute