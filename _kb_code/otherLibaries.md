---
layout: doc
title: Other Libraries
category: code
parent: Libraries
---

## [noUiSlider](https://refreshless.com/nouislider/)

A simple range slider that has a lot of options and is easily customizable.

## GUP

Code written by [Axis Maps'](http://www.axismaps.com) own Dave Heyman. Grabs values from the URL query string and returns the result in a JS object.

```
function gup( name ){
  name = name.replace(/[\[]/,"\\\[").replace(/[\]]/,"\\\]");
  var regexS = "[\\?&]"+name+"=([^&#]*)";
  var regex = new RegExp( regexS );
  var results = regex.exec( window.location.href );
  if( results == null )
    return "";
  else
    return results[1];
}
```

## [Normalize.css](https://necolas.github.io/normalize.css/)

A CSS reset file that resets all CSS rules to a standard style. Each browser can have their own rulesets for various styles; a reset file sets all the differing styles to a single standard.

## [Featherlight](http://noelboss.github.io/featherlight/)

A simple JQuery lightbox. Works on IE 8+ and mobile as well as the evergreen browsers.

## [PapaParse](http://papaparse.com/)

A powerful library that parses CSV and returns a JS object.
