# Instructions

What if you want to create a greeting with the name?

## Steps

1. At line 2, create a variable `greetings` and assign it to the formatted string as such:

```javascript
const name = 'Bob';
const greetings = `Hello ${name}`;
```

Essentially, this is the same as:

```javascript
const greetings = 'Hello Bob';
```

2. Print `greetings`, run the code, and it would show in the console (on the right):

```
Hello Bob
```

3. If you change `name` variable from `Bob` to `Charlie` at line 1, and run the code, it should show:

```
Hello Charlie
```

<details>
<summary>Full code</summary>

```javascript
const name = 'Charlie';
const greetings = `Hello ${name}`;
```

</details>

## Explanation of template literals

```javascript
`Hello ${name}`
```

In JavaScript, you can use backticks (`` ` ``) instead of single or double quotes to create a template literal. This allows you to embed expressions directly into the string.

### Why use template literals?

Because, sometimes we have different values for the variables.

Inside the template literal, we also see ${curly brackets}. This is where you put a variable.

```javascript
const name = 'Bob';
const greetings = `Hello ${name}`;
```

Essentially, this is the same as:

```javascript
const greetings = 'Hello Bob';
```
