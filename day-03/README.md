# Day 03 - Challenge 3: Operators

## Topic

Arithmetic and comparison operators

## Goal

Practice calculating values and comparing results with simple expressions.

## Challenge

Build a small calculator that works with two numbers and prints the result of a few operations.

### Requirements

- Declare two numeric values.
- Calculate sum, difference, product, and quotient.
- Check whether the first value is greater than the second.
- Log all results in a readable summary.

### Example Output

```text
Sum: 15, Difference: 5, Product: 50, Quotient: 2, Is first greater? true
```

## Stretch Goal

Include the remainder using the modulus operator.

## Starter Code

```js
const firstNumber = 10;
const secondNumber = 5;

const sum = firstNumber + secondNumber;
const difference = firstNumber - secondNumber;
const product = firstNumber * secondNumber;
const quotient = firstNumber / secondNumber;
const isFirstGreater = firstNumber > secondNumber;

console.log(
  `Sum: ${sum}, Difference: ${difference}, Product: ${product}, Quotient: ${quotient}, Is first greater? ${isFirstGreater}`,
);
```

## What To Learn

- Arithmetic operators
- Comparison operators
- How expressions produce values
