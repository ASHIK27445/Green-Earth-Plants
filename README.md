# Green Earth Plants 
## What is the difference between var, let, and const?
The differences between var, let, and const in JavaScript mostly come down to how they behave in different situations. var is old-school and works within the function it’s declared in, but you can both change its value and declare it again in the same function. By default, it starts as undefined. let, on the other hand, is more modern and works within the block of code it’s in (like inside loops or conditionals). You can change its value, but you can’t declare it twice in the same block, and it won’t be initialized until you give it a value. const is similar to let in that it works within a block, but once you give it a value, it can’t be changed, and you have to give it a value right when you declare it. So, while var is more flexible but outdated, let and const offer more control over your code.

## What is the difference between map(), forEach(), and filter()?
forEach() is used when you want to perform an action on each element of an array without changing the array itself or creating a new one. <br> 
map() is for when you need to change the elements in the array and create a brand-new array with the updated values. <br> 
filter() is used when you want to pick certain elements from the array based on a condition, and it creates a new array with only the elements that meet that condition.

## What are arrow functions in ES6?
Arrow functions in ES6 provide a shorter and simpler way to write functions. They use the => syntax and automatically take the this value from the surrounding context, which makes them great for things like callback functions or methods inside objects. Unlike regular functions, arrow functions don't have their own this, arguments, super, or new.target, so they behave a bit differently in some cases. They're especially useful when you need a quick, one-liner function or want to avoid manually dealing with this. <br>
Example: <br>
```js
        const add = (a, b) => a + b; 
```
In this case, the add function takes two parameters and returns their sum, all in one line

## How does destructuring assignment work in ES6?
Destructuring assignment in ES6 is a convenient way to unpack values from arrays or objects and assign them to variables. With arrays, you can easily extract values by their position, and with objects, you can extract values by their keys.

## Explain template literals in ES6. How are they different from string concatenation?
Template literals in ES6 make working with strings much easier and cleaner. Instead of using regular quotes, you enclose the string in backticks (`). What makes them special is that you can easily embed variables or expressions directly inside the string using ${}. <br> using template literals:
```js
        const name = 'Hero'
        const message = `Hello, ${name}!`
```
This is much cleaner than doing string concatenation like:
```js
        const message = 'Hello, ' + name + '!'
```


