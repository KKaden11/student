---
toc: False
layout: post
title: Data Abstraction!
description: Data Abstraction blog post.
categories: [Foundation]
permalink: /foundation/data-abstraction/
---

## Data Abstraction

This blog is about data abstraction.

### HOMEWORK

This is a code of a calculator. Please read through the code first to try and understand what it does.
There are many unnecessary lines within the code. Please identify the unnecessary lines and delete them.

```javascript
// Cleaned version with unnecessary lines removed
function calculator(num1, num2, operator) {
  let result;

  if (operator === "+") {
    result = num1 + num2;
  } else if (operator === "-") {
    result = num1 - num2;
  } else if (operator === "*") {
    result = num1 * num2;
  } else if (operator === "/") {
    result = num1 / num2;
  } else {
    result = "Invalid operator";
  }

  return result;
}

console.log(calculator(10, 5, "+"));
console.log(calculator(10, 5, "-"));
console.log(calculator(10, 5, "*"));
console.log(calculator(10, 5, "/"));
```

### Output (Solved)

```text
15
5
50
2
```
