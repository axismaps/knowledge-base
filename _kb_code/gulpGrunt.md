---
layout: doc
title: Gulp vs Grunt
category: code
parent: Build Tools
---

## Overview

Gulp and Grunt are two of the more popular build tools. These are Command Line tools that process your files and put them in a state to be published on the web. This can include uglifying your Javascript, concatenating files, etc...

Some of the things we use the build tool for:
- Uglify Javascript (minimizes it)
- Concatenate all Javascripts files
- Post-process CSS (add prefixes)
- Concatenate all CSS files
- Rename files (versioning)
- Minify images
- Move fonts, data files, etc... into a `Public` folder

## Gulp

Write the build process in standard Javascript. This is the one we use.

## Grunt

A configuration file based build tool. There are many config files available on the internet.
