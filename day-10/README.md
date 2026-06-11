# Day 10 - Challenge 10: Arrow Functions

## Topic

Arrow functions in JavaScript

## Goal

Practice writing shorter function expressions with arrow syntax.

## Challenge

Convert a regular function into an arrow function and use it in a simple calculation.

### Requirements

- Create a function with arrow syntax.
- Accept at least two parameters.
- Return a value from the function.
- Log the result to the console.

### Example Output

```text
Sum: 15
```

## Stretch Goal

Write a second arrow function that uses an implicit return.

## Starter Code

```js
const addNumbers = (firstNumber, secondNumber) => {
  return firstNumber + secondNumber;
};

console.log(`Sum: ${addNumbers(10, 5)}`);
```

## What To Learn

- Arrow function syntax
- Returning values from expressions
- Why concise functions are useful
