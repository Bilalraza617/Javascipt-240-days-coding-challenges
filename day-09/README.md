# Day 09 - Challenge 9: Functions

## Topic

Functions and reusable logic

## Goal

Practice putting logic inside reusable functions.

## Challenge

Build a function that greets a person by name and optionally includes their city.

### Requirements

- Create a function that accepts at least one parameter.
- Return a custom greeting string.
- Call the function more than once with different inputs.
- Print the results to the console.

### Example Output

```text
Hello, Ali!
Hello, Sara from Karachi!
```

## Stretch Goal

Add a default value for the city parameter.

## Starter Code

```js
function greet(name, city = "") {
  if (city) {
    return `Hello, ${name} from ${city}!`;
  }

  return `Hello, ${name}!`;
}

console.log(greet("Ali"));
console.log(greet("Sara", "Karachi"));
```

## What To Learn

- Function declarations
- Parameters and return values
- Reuse through abstraction
