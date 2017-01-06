---
layout: doc
title: File Layout
category: code
parent: Code Layout
---

There are many many ways to handle file management on projects. We use a simple one as follows:

- **index.html** - handles adding all the CSS/JS files and is the main location for HTML (we try to stay away from Javascript based HTML creation).
- **bower.json** - is the Bower config file (see the [Bower vs NPM](/code/bowerNpm/index.html) article for more details)
- **/js** - all Javascript
- **/css** - all CSS
- **/img** - stores any images
- **/data** - stores any non-tile data - *e.g. CSV files, JSON files, etc...*
- **/tiles** - stores any raster tiles that may be needed for the project
- **/bower_components** - an auto-generated folder (with the command `bower install`) of the various libraries Bower has on file in `bower.json`
