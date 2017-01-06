---
layout: doc
title: JS Best Practices
category: code
parent: Code Best Practices
---

## IIFE

Immediately invoked function expressions (IIFE) are a way to keep variables in scope within the function. It's a nice way to make sure none of your variables conflict with any plugins' or libraries' variables. Each IIFE contains the variables within it's own scope so using one per file or even more helps to keep your variables from conflicting.

IIFE is an older way of handling scope and global variables. They work across all browsers so if newer ways of handling scope don't work (*e.g. let and const*) this will work. Ben Alman has a good summary of [why it is useful](http://benalman.com/news/2010/11/immediately-invoked-function-expression/).

It is written like this:

```
(function () {
  // Your code goes here
})();
```
