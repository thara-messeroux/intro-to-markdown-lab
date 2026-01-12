# Writing a Function in JavaScript

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1600)

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition.  
Here’s a brief tutorial on writing an arrow function in JavaScript.

---

## 1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

- **const**: `const` should be used whenever a function expression is assigned to a variable.
- **The function name**: The name you choose for the function.
- **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the `()` is still required.
- **The arrow syntax**: Indicates that this will be a function.
- **The body**: The statements that make up the function itself. Surrounded by curly braces.

**Example:**

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does.  
> Examples include `fetchData()`, `calculateArea()`, or `printReport()`.

---

## 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

**Example:**

```javascript
greet("Alice"); // Outputs: Hello, Alice!
```

---

## 3. Return values

Functions can process data input and output a value using the `return` keyword.

**Example:**

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total); // Expected value: 6
```

For more information on functions and how they are used in JS, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions).

---

## Quick reference (table)

| Concept | What it means |
| --- | --- |
| **call / invoke** | Run a function |
| **return** | Send a value back |

---

## Part 2: Create another tutorial (30 min)

1. Create a new file with a `.md` extension.
2. Choose a new topic (a few options for inspiration):
   - How to write an HTML Boilerplate
   - The anatomy of a CSS selector
   - How to create a file using the Terminal
   - How to build the perfect sandwich
3. Practice your new skills by writing another short tutorial in Markdown!

### Checklist (for Part 2)

- [ ] Create a new `.md` file
- [ ] Add at least 2 headings
- [ ] Include 1 code block
- [ ] Include 1 link
- [ ] Include 1 image
- [ ] Push to GitHub

---

## Reference-style link (extra practice)

This is a reference-style link to [MDN Functions][mdn-functions].

[mdn-functions]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
