---
layout: doc
title: Coding Libraries
category: code
parent: Libraries
---

### jQuery

Though jQuery is falling out favor, it still is very useful, especially if you have to support older versions of IE. jQuery is very good for handling simple user interactions; more complex UI libraries and/or frameworks are not really needed for interactive maps.

It's [custom event handling](https://learn.jquery.com/events/introduction-to-custom-events/) is useful for passing events back and forth between the UI and the mapping library.

### Underscore

Underscore has a lot of practical low level functions. Many of them are being slowly worked into the Javascript language proper, but Underscore works in browsers that don't yet support these functions. For example, `map` and `reduce` are only supported by IE9+. It also has some convenience functions such as `_.find`. Finally, it has the `_.chain` function that is very useful in data processing.
