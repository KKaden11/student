---
toc: False
layout: post
title: Mathematical Expressions
description: Mathematical Expressions blog post.
categories: [Foundation]
permalink: /foundation/mathematical-expressions/
---

## Mathematical Expressions

### Introduction

Mathematical expressions in coding are combinations of numbers, variables, and operators used to calculate values in a program.

```javascript
1 + 2 * 3; // 7
```

Math in JavaScript follows the same core rules as regular math, just written in code syntax.

### Key Mathematical Operators

| Operator | Symbol | Example | Result |
| --- | --- | --- | --- |
| Addition | `+` | `2 + 3` | `5` |
| Subtraction | `-` | `5 - 2` | `3` |
| Multiplication | `*` | `4 * 3` | `12` |
| Division | `/` | `10 / 2` | `5` |
| Modulo | `%` | `7 % 3` | `1` |
| Exponentiation | `**` | `2 ** 3` | `8` |

You can also use comparison operators in conditions, like `>`, `<`, `==`, `<=`, and `>=`.

### Variables in Expressions

You can store values in variables and use them in calculations:

```javascript
let x = 10;
let y = 3;
let total1 = x + y + 2;

console.log("The total is: " + total1);
```

### Order of Operations (PEMDAS)

JavaScript evaluates expressions in this order:

- Parentheses
- Exponents
- Multiplication/Division
- Addition/Subtraction

### Modulo Example (Even/Odd Check)

Modulo gives the remainder after division and is useful for checking divisibility.

```javascript
let x = 17;
let total = x % 2;

console.log(x + " % 2 = " + total);

if (x % 2 === 0) {
  console.log(x + " number is even");
} else {
  console.log(x + " number is odd");
}
```

### Practice Challenges

1. Find and fix the syntax error:

```javascript
let number = 5;
console.log(number;); // fix this
```

2. Change values of `x` and `y`, then observe output changes:

```javascript
let x = 10;
let y = 3;
let total1 = x + y + 2;

console.log("The total is: " + total1);
```

3. Use modulo to test even/odd for different values of `x`:

```javascript
let x = 17;
if (x % 2 === 0) {
  console.log(x + " number is even");
} else {
  console.log(x + " number is odd");
}
```

4. Homework Problem: Create a program that checks if a number `y` is divisible by 5.

5. Homework Problem: Create a program with variables `a`, `b`, and `sum`, then print the result.
