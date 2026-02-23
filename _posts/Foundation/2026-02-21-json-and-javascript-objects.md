---
toc: False
layout: post
title: JSON and JavaScript Objects
description: JSON and JavaScript Objects blog post.
categories: [Foundation]
permalink: /foundation/json-and-javascript-objects/
---

## JSON and JavaScript Objects

This blog is about JSON and JavaScript objects.

### Homework Assignment: JSON Challenge

Create a resume containing your personal information, skills, and education and print it as a JSON string.

```javascript
// 1. Create a JavaScript object named `resume`
const resume = {
  fullName: "Kaden Arp",
  email: "kadenarp@gmail.com",
  education: "Grade 9",
  address: {
    city: "San Diego",
    state: "California",
    country: "United States"
  },
  skills: ["JavaScript", "HTML", "CSS"]
};

// 2. Access and display properties using dot notation
console.log("Full Name:", resume.fullName);
console.log("Email:", resume.email);
console.log("City:", resume.address.city);

// 3. Convert object to JSON string
const jsonString = JSON.stringify(resume);
console.log("jsonString:", jsonString);

// 4. Parse JSON string back to JavaScript object
const parsedResume = JSON.parse(jsonString);
console.log("parsedResume:", parsedResume);
```

### Output (Solved)

```text
Full Name: Kaden Arp
Email: kadenarp@gmail.com
City: San Diego
jsonString: {"fullName":"Kaden Arp","email":"kadenarp@gmail.com","education":"Grade 9","address":{"city":"San Diego","state":"California","country":"United States"},"skills":["JavaScript","HTML","CSS"]}
parsedResume: {
  fullName: 'Kaden Arp',
  email: 'kadenarp@gmail.com',
  education: 'Grade 9',
  address: { city: 'San Diego', state: 'California', country: 'United States' },
  skills: [ 'JavaScript', 'HTML', 'CSS' ]
}
```
