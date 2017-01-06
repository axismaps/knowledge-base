---
layout: doc
title: CSS Best Practices
category: code
parent: Code Best Practices
---

## [BEM](http://getbem.com/)

BEM is a naming scheme that aims to prevent style conflicts and the arms race that can occur in CSS rule sets. It stands for Block-Element-Modifier. It is gets progressively more useful the larger your project gets, but is still useful in small code bases. A good primer on BEM can be found at [getbem.com/introduction](http://getbem.com/introduction/).

## Flexbox

Flexbox is a group of CSS rules that are extremely useful for responsive layouts. IE 11+ and all the Evergreen browsers support Flexbox. IE 10 also does, but with different [rule names](https://msdn.microsoft.com/en-us/library/hh673531(v=vs.85).aspx). A good primer on Flexbox can be found on [css-tricks.com](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

Flexbox was written into specifications specifically for layout. `Float` and `display: table` are no longer considered good ways to do layout (though you may have to resort to them in certain cases - especially if you have to support pre-IE 10 browsers).
