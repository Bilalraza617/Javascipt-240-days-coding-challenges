# Day 01 - Challenge 1: Variables

## Topic

Variables in JavaScript

## Goal

Practice `let`, `const`, and `var` by building a small profile card object from basic user details.

## Challenge

Create a small JavaScript script that stores information about a learner and prints a formatted summary.

### Requirements

- Declare the learner's name, age, and city using variables.
- Use `const` for values that should not change.
- Use `let` for any value that may be updated.
- Create a final message that combines the values into one readable sentence.
- Log the result to the console.

### Example Output

```text
Name: Ali, Age: 21, City: Lahore
```

## Stretch Goal

Add one more variable for the learner's favorite programming language and include it in the output.

## Starter Code

```js
const learnerName = "Ali";
let learnerAge = 21;
const learnerCity = "Lahore";

console.log(`Name: ${learnerName}, Age: ${learnerAge}, City: ${learnerCity}`);
```

## What To Learn

- When to use `let` and `const`
- How variables store data
- How to build a readable output from stored values
