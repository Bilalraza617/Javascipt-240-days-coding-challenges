# Day 06 - Challenge 6: Conditionals

## Topic

If, else if, and else statements

## Goal

Practice making decisions based on a value.

## Challenge

Write a script that tells whether a student passed, needs improvement, or failed based on a score.

### Requirements

- Declare a score between 0 and 100.
- Use at least one `if`, one `else if`, and one `else`.
- Show different messages for high, medium, and low scores.
- Log the final decision to the console.

### Example Output

```text
Grade: A - Excellent work
```

## Stretch Goal

Convert the score into a letter grade from A to F.

## Starter Code

```js
const score = 87;

if (score >= 90) {
  console.log("Grade: A - Excellent work");
} else if (score >= 75) {
  console.log("Grade: B - Good job");
} else {
  console.log("Grade: Needs improvement");
}
```

## What To Learn

- Decision making with conditions
- Comparison operators inside branches
- How to structure readable flow
