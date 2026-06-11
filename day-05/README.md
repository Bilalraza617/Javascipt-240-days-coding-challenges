# Day 05 - Challenge 5: Template Literals

## Topic

Template literals and formatted strings

## Goal

Practice building readable output with embedded values and multiline strings.

## Challenge

Create a student introduction message using template literals.

### Requirements

- Store a name, age, and city in variables.
- Build one message using backticks.
- Include at least one expression inside the template literal.
- Print the result to the console.

### Example Output

```text
My name is Ali, I am 21 years old, and I live in Lahore.
```

## Stretch Goal

Create a multiline profile card using one template literal.

## Starter Code

```js
const name = "Ali";
const age = 21;
const city = "Lahore";

console.log(
  `My name is ${name}, I am ${age} years old, and I live in ${city}.`,
);
```

## What To Learn

- How template literals work
- Embedding variables inside strings
- Making output cleaner and easier to read
