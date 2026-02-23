---
toc: False
layout: post
title: Iterations
description: Iterations blog post.
categories: [Foundation]
permalink: /foundation/iterations/
---

## Iterations

This blog is about iterations.

### Challenge Iteration

Write an iteration to calculate the sum of all numbers from `1` to `n`.
Test it with an input of `5`.

```javascript
// Complete function to sum numbers from 1 to n
function sumNumbers(n) {
  let sum = 0;

  for (let i = 1; i <= n; i++) {
    sum += i;
  }

  return sum;
}

const result = sumNumbers(5);
console.log("Sum from 1 to 5:", result);
```

### Output (Solved)

```text
Sum from 1 to 5: 15
```
