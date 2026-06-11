# Day 08 - Challenge 8: Nested Loops

## Topic

Nested loops in JavaScript

## Goal

Practice repeating logic inside another loop.

## Challenge

Create a multiplication table or simple grid using nested loops.

### Requirements

- Use one loop inside another loop.
- Print rows and columns in a structured way.
- Show a clear visual pattern or table in the console.
- Log the output to the console.

### Example Output

```text
1 x 1 = 1
1 x 2 = 2
2 x 1 = 2
```

## Stretch Goal

Print a 5x5 pattern of stars.

## Starter Code

```js
for (let row = 1; row <= 3; row++) {
  for (let column = 1; column <= 3; column++) {
    console.log(`${row} x ${column} = ${row * column}`);
  }
}
```

## What To Learn

- How nested loops work together
- Repeating patterns with two counters
- Building table-like console output
