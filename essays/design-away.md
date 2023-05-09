---
layout: essay
type: essay
title: "Designing in Cyberspace"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Design Patterns
  - Software Engineering
  - Decisions
---

*Design Patterns Save Lives*

## What are they?

Design patterns are like tried and true recipes that ensure the software architecture is flexible, scalable, and easy to maintain over time. Just like in construction where architects use a set of standardized building blocks based on strength, durability and cost-effectiveness, software developers choose design patterns based on their suitability, reusability and maintainability. They provide a common vocabulary for developers to communicate and collaborate. This reduces the development time and cost of software systems. They also allow teams to adapt to changing business requirements quicker, saving time and money.

## The Good and the Bad

Just like one man's trash is another man's treasure, a specific design pattern will work great for a specific project and team, but will not work at all for another project and team. Each design pattern has its own place. The God Object pattern is an anti-pattern that occurs when a single object or class is responsible for too many tasks. This pattern can make the code difficult to maintain and extend. For example, if we have a class that handles database connections, input validation, user authentication, and more, we are likely to run into problems as the application grows and changes. But what if we have a small command-line utility that performs a single, simple task, and we do not expect it to grow or change in any significant way. then the God Object pattern would be a smashing hit!


## My Own Experience

In my own experience, I have found that design patterns are an essential. In my EE 367 class, I experienced a large C codebase that had no design pattern, no tests, no documentation, and it was a total b**** to expand upon. (It was also a socket based network program, which made things so much worst). In contrast, my hackathon experience used the Django web framework, which has the Model View Controller design pattern embedded into it. Coding in that paradigm with a team was a breeze. I'm definitely going to use a solid design pattern on any future project.

