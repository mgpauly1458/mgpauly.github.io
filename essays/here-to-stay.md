---
layout: essay
type: essay
title: "Javascript Is Here To Stay"
# All dates must be YYYY-MM-DD format!
date: 2023-01-18
published: true
labels:
  - Engineering
---

<img width="200px" class="rounded float-start pe-4" src="../img/javascript-logo.png">

*Javascript has turned into a monster, but is it already too late...*

I’m quite experienced with javascript for a college student. I’ve made many websites for friends, family, and just for fun. I’ve used frameworks like Express, React, Node, Angular, Three.js, Roslib.js, and countless other node packages to accomplish various tasks that come up (converting and displaying dates, or sending text messages using Twilio). Javascript is easy to use and understand, but I feel as if its lacking certain programming language / runtime constraints that would make it an ideal language for large system development.

## Javascript Should Be Statically Typed

Javascript should really be statically typed at this point. It is important to remember javascript started off as a simple language that allowed you to manipulate elements on the DOM. Such as changing the color of a word on a webpage when a button was clicked. Because of its initial image, I think the designers of javascript didn’t consider making it statically typed, because they didn’t think large systems would one day be built with it. But it has evolved into a language capable of many different paradigms of computing. It can do frontend, backend, graphics rendering, networking, bit-level manipulation of data, audio manipulation, AJAX and REST APIs, and the list goes on. With this level of complexity, the arguments and return types of functions should really be defined. TypeScript tried to solve this problem and organizations report switching to typescript has caught more errors than they imagined they had. But to me this seems like a bandaid on the problem. The problem is really at the language’s core, but it seems too late to change something as big as that with all the development already done with javascript.

## The Event Loop :thumbsdown:

I’m also not a huge fan of the event loop. Modern javascript engines have in my opinion a “round-about” way of handling asynchronous tasks, where they are queued in the event loop and checked on after each pass. Promises seem to have the largest learning curve of any javascript feature, and to me this is unnecessary. In 2023 javascript should really be capable of multiple threads. With javascript being able to access the hardware directly, there should be a more standardized and speedy way to do more than one thing at once. Especially with processor clock speeds maxing out, leaving manufacturers the only option of adding cores to speed up their hardware.

## Companies Have It Easy

Overall I’m quite impressed with how far javascript has come. I do like that a company needs to only require javascript experience from its employees in order to have access to essentially every computing paradigm possible. The community seems to really enjoy javascript, but it does get criticism from industry gurus for some of the same reasons I’ve stated here. Sometimes I wonder what our world would look like if Node.js was never invented? Javascript has put too many band aids on itself in order to stay with the times. But I don’t think it's going anywhere anytime soon.
