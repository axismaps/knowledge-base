---
layout: doc
title: iMagick
category: code
parent: Build Tools
---

## Overview

[iMagick](https://www.imagemagick.org/script/index.php) is a PHP based Command Line tool that is focused on image manipulation. It is good for generating thumbnails and converting between image formats.

## Some useful snippets

#### Create single thumbnail:
Resizes and crops a single file. Create a single thumbnail.
- *does not overwrite the file*
- *quotes around 280x280^ are important on Windows*

```
convert test.jpg -resize "280x280^" -gravity center -crop 280x280+0+0 thumb.jpg
```

#### Create multiple thumbnails:
Resize and crop a bunch of files. Create a batch of thumbnails.
- *this command will overwrite the files*
- *quotes around 280x280^ are important on Windows*

```
mogrify -resize "280x280^" -gravity center -crop 280x280+0+0 *.jpg
```
