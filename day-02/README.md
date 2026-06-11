# Day 02 - Challenge 2: Data Types

## Topic

JavaScript data types and type checking

## Goal

Practice identifying values with `typeof` and formatting a simple data summary.

## Challenge

Create a script that stores a few different values and prints their types in a readable format.

### Requirements

- Declare one string, one number, one boolean, and one undefined value.
- Use `typeof` to check each value.
- Combine the results into one summary message.
- Log the final message to the console.

### Example Output

```text
name is string, age is number, isStudent is boolean, score is undefined
```

## Stretch Goal

Add a null value and note the special behavior of `typeof null`.

## Starter Code

```js
const name = "Ali";
const age = 21;
const isStudent = true;
let score;

console.log(
  `name is ${typeof name}, age is ${typeof age}, isStudent is ${typeof isStudent}, score is ${typeof score}`,
);
```

## What To Learn

- Primitive data types in JavaScript
- How `typeof` works
- Why undefined and null behave differently
