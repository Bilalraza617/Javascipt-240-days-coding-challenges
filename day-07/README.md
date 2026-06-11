# Day 07 - Challenge 7: Loops

## Topic

For loops and repeated actions

## Goal

Practice repeating work without copying code.

## Challenge

Create a script that prints numbers from 1 to 10 and marks the even ones.

### Requirements

- Use a loop that runs 10 times.
- Print each number in order.
- Mark whether each number is even or odd.
- Log the output to the console.

### Example Output

```text
1 is odd
2 is even
3 is odd
```

## Stretch Goal

Sum all numbers from 1 to 10 and print the total.

## Starter Code

```js
for (let number = 1; number <= 10; number++) {
  const type = number % 2 === 0 ? "even" : "odd";
  console.log(`${number} is ${type}`);
}
```

## What To Learn

- Loop control
- Repetition with counters
- Using conditions inside loops
