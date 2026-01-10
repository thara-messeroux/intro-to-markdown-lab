Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

1. **const**: const should be used whenever a function expression is assigned to a variable.
2. **The function name**: The name you choose for the function.
3. **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
4. **The arrow syntax**: Indicates that this will be a function.
5. **The body**: The statements that make up the function itself. Surrounded by curly braces.

***Example***:

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

**Tip**: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

***Example***:

```javascript
greet('Alice'); // **Outputs**: Hello, Alice!
```

3. Return values

Functions can process data input and output a value using the *return* keyword.

***Example***: 

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // **Expected value**: 6
```

For more information on functions and how they are used in JS, check out the MDN docs. 
[Mozilla](
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)


# h1
## h2
### h3
#### h4
##### h5
###### h6



This text is **bold**. This text is also __bold__.

This text is in *italics*. This text is also in _italics_.


**const**: ...
**The function name**: ...
**Parameters**: ...
**The arrow syntax**: ...
**The body**: ...

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
  

Use the `console.log()` function to print values to the console.


```javascript
const printItem = (item) => {
  console.log(item);
}
```


[Google](https://www.google.com)

This is [a reference][example].

[example]: http://www.example.com/


