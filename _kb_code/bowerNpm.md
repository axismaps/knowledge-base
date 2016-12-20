---
layout: doc
title: Bower vs NPM
category: code
parent: Build Tools
---
## Overview

Bower and NPM are command line tools that help with installing libraries/frameworks for use in your project. They keep a config file that makes it easy for other developers to install the same packages, plus, there is no confusion about versions as the config file stores version information as well.

Bower is built on top of NPM, so the first step for either of these tools is to [install NPM](http://blog.npmjs.org/post/85484771375/how-to-install-npm).

## Bower

Bower has been losing popularity lately (for one reason, it is built on NPM), but we still use it for most of our projects. It is simple and easy to use and a lot of popular packages support it. You can also use Bower with any Github repository which is nice for small plugins that aren't necessarily published.

## NPM

The current install tool of choice. d3 doesn't support bower anymore, so it is easier to use NPM if starting a d3 project.
