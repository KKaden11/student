---
toc: False
layout: post
title: Conditionals
description: Conditionals blog post.
categories: [Foundation]
permalink: /foundation/conditionals/
---

## Conditionals

This blog is about conditionals.

### Popcorn Hack 1 - Simple Conditionals (Solved)

```javascript
const mood = "happy";

if (mood === "happy") {
  console.log("You are happy, go get ice cream!");
} else if (mood === "tired") {
  console.log("Take a break and rest.");
} else {
  console.log("Have a good day!");
}
```

### Output (Solved)

```text
You are happy, go get ice cream!
```

### Popcorn Hack 2 - Vending Machine (Solved)

```javascript
const snackChoice = "1"; // 1=chocolate, 2=chips, 3=candy

if (snackChoice === "1") {
  const chocolateType = "milk";

  if (chocolateType.toLowerCase() === "milk") {
    console.log("You got a milk chocolate bar!");
  } else if (chocolateType.toLowerCase() === "dark") {
    console.log("You got a dark chocolate bar!");
  } else {
    console.log("Unknown chocolate type.");
  }
} else if (snackChoice === "2") {
  console.log("You got chips!");
} else if (snackChoice === "3") {
  const candyColor = "red";

  if (candyColor.toLowerCase() === "red") {
    console.log("You got red candy!");
  } else if (candyColor.toLowerCase() === "green") {
    console.log("You got green candy!");
  } else if (candyColor.toLowerCase() === "yellow") {
    console.log("You got yellow candy!");
  } else {
    console.log("Unknown candy color.");
  }
} else {
  console.log("Invalid snack choice.");
}

if (Math.random() < 0.1) {
  console.log("Bonus treat! The machine gives you an extra cookie!");
}
```

### Output (Solved)

```text
You got a milk chocolate bar!
```

### Homework (Solved)

```javascript
// 1) temperature conditional
const temperature = 85;
if (temperature > 80) {
  console.log("It’s hot outside!");
} else {
  console.log("It’s nice outside.");
}

// 2) score letter grade
const score = 88;
if (score >= 90) {
  console.log("A");
} else if (score >= 80) {
  console.log("B");
} else if (score >= 70) {
  console.log("C");
} else {
  console.log("Needs improvement.");
}

// 3) function for score input
function getLetterGrade(userScore) {
  if (userScore >= 90) return "A";
  if (userScore >= 80) return "B";
  if (userScore >= 70) return "C";
  return "Needs improvement.";
}

const inputScore = 92; // example user input
console.log("Input score grade:", getLetterGrade(inputScore));

// 4) even/odd
const number = 7;
if (number % 2 === 0) {
  console.log("Even Number");
} else {
  console.log("Odd number.");
}

// 5) random integer 1-10 (sample generated value shown)
const randomNumber = 6;
if (randomNumber % 2 === 0) {
  console.log("Random number:", randomNumber, "- Even Number");
} else {
  console.log("Random number:", randomNumber, "- Odd number.");
}

// 6) switch on day
const day = "Saturday";
switch (day) {
  case "Monday":
    console.log("Start of the school week.");
    break;
  case "Friday":
    console.log("Almost the weekend!");
    break;
  case "Saturday":
    console.log("Relax, it is Saturday.");
    break;
  case "Sunday":
    console.log("Prepare for Monday.");
    break;
  default:
    console.log("Regular weekday.");
}

// 7) weekend vs weekday
if (day === "Saturday" || day === "Sunday") {
  console.log("Weekend!");
} else {
  console.log("Weekday!");
}

// 8) loggedIn boolean
const loggedIn = true;
if (loggedIn) {
  console.log("Welcome back!");
} else {
  console.log("Please log in.");
}

// 9) weather conditional
const weather = "raining";
if (weather === "raining") {
  console.log("It's raining.");
} else {
  console.log("Go outside, it's a nice day today!");
}
```

### Output (Solved)

```text
It’s hot outside!
B
Input score grade: A
Odd number.
Random number: 6 - Even Number
Relax, it is Saturday.
Weekend!
Welcome back!
It's raining.
```
