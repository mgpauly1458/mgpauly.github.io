---
layout: essay
type: essay
title: "Integration Hell And How To Avoid It"
# All dates must be YYYY-MM-DD format!
date: 2023-01-18
published: true
labels:
  - Integration Hell
  - IDE
  - Git
  - ESLint
---

<img width="200px" class="rounded float-start pe-4" src="../img/mergeMeme.jpg">

## Game Changer

After learning more about version control, Integrated Development Environments, linting tools, and coding standards, I have a much better feel of what it means to develop software “correctly”. I’ve made a ton of little 50 lines or less projects, but I’ve never made a really big robust system that many developers contributed to. It feels like the concepts I listed above are a necessary prerequisite for any meaningful software project, and they should be embedded into any software engineer's brain.

## Personal Experience

Myself and a few friends submitted an entry to the 2021 Hawaii Annual Coding Challenge (HACC). This was a non-traditional hackathon that spanned about three weeks. We were tasked with making an app that can help the Department of Land and Natural Resources (DLNR) track the foot traffic on Hawaii’s hiking trails. Over three weeks, three of us inexperienced developers created a full stack web application that was semi-complex. A thorough list of its features can be found in the project post I made [here](https://mgpauly1458.github.io/projects/hawaii-annual-coding-challenge.html). The point is we were cloning, and merging, and pushing, and rebasing, and reverting, and resetting, and cloning, and editing each other's code and it was madness. I’ll never forget what breaking the repo felt like because I used the wrong git command, and I’ll never forget the pain it caused us to untangle eachothers code because we didn’t have a good system set in place. Half the time we couldn’t even understand each other's code, so we had to pull one another aside for help which completely destroyed that developer’s focus if he was working on something. We didn’t use any of the concepts listed above and were kind of just winging it.

## Post Mortem

After breaking our build and fixing it, and breaking our build and fixing it what felt like hundreds of times we finally got it to work and submitted it. We pulled several all nighters to make that happen. We came together after the hackathon was over and talked about what we could do better next time in a post mortem meeting. We confessed our tests and integration procedures took way too much time, and we should conform to standard integration practices like version control, test frameworks, using a linter, having team based commit/build standards, and keeping our code clean and DRY.

## Vow of Excellence

After that painful learning experience I forced myself to master the git basics. And from here on, I vow to never write another line of code for a project until a test is written, a build script is made which only takes one command to completely build the project, have a shared development database and deployment database which are separate from one another, and have a standard linting tool that checks the code of each developer. With the experience I’ve had with ESLint and IntelliJ, I realized that setting these things up isn’t that painful after all. It feels good to get that green check mark in IntelliJ and look at my spectacular looking code at the end. After watching the screen casts and using these tools, I’m quite excited to start another project with others, and do it all over again but the right way this time.

