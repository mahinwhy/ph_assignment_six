## 1) What is the difference between `var`, `let`, and `const`?

- **let**: We can reassign value anywhere. Can be declared without being initialized.  
- **const**: We cannot reassign value in the same scope, but we can modify elements of arrays and objects.  
- **var**: We can reassign and re-initialize it anywhere.  

---

## 2) What is the difference between `map()`, `forEach()`, and `filter()`?

- **map()**: Used for transforming an array. Returns a new array with transformed elements.  
- **forEach()**: Used when we want to perform a function on all elements of a loop. It is simply a loop.  
- **filter()**: Used for selecting or filtering elements from an array. Returns a new array with the selected elements.  

---

## 3) What are arrow functions in ES6?

Arrow functions are a simpler way of writing functions.  
They do not support the `arguments` object and `this` works differently compared to normal functions.  

```js
        const add = (a, b) => a + b;
```js

## 4) How does destructuring assignment work in ES6?

Destructuring assignment allow initializing multiple variable from array or object. It is a clean and readable way of extracting data from array or object.

```js
        const num = [1, 2, 3];
        const [a, b] = num; // a = 1, b = 2
```js
       
## 5) Explain template literals in ES6. How are they different from string concatenation?

Template literals provide us a more readable code while making a string. It will allow us use variable without using "+" and will allow us to write multiline strings. We have to use (`) instead of (") or (').

```js
        const sub = 'World';
        const greeting = `Hello ${sub}!`; //Hello World!