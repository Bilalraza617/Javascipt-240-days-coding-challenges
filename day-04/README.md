# Day 04 - Challenge 4: Type Conversion

## Topic

Type conversion in JavaScript

## Goal

Practice converting strings, numbers, and booleans into different types.

## Challenge

Create a small script that takes raw input values and converts them into usable types.

### Requirements

- Declare a numeric value as a string.
- Convert it into a number.
- Convert a number into a string.
- Convert a value into a boolean.
- Log the converted results to the console.

### Example Output

```text
Converted age: 21, age type: number, isActive: true
```

## Stretch Goal

Handle an invalid numeric string and show what conversion returns.

## Starter Code

```js
const rawAge = "21";
const age = Number(rawAge);
const isActive = Boolean(1);

console.log(
  `Converted age: ${age}, age type: ${typeof age}, isActive: ${isActive}`,
);
```

## What To Learn

- Explicit conversion with `Number`, `String`, and `Boolean`
- Implicit versus explicit type changes
- How type conversion affects data before logic runs
