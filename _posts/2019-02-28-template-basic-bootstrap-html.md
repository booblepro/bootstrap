---
layout: post
title: "Bootstrap 4.1.3 Boilerplate with Gulp"
theme: "Basic"
subtitle: "A Bootstrap 4.1.3 Boilerplate with Sass and Gulp"          
categories:
    - HTML
    - Popular
version:
    - Bootstrap 4.1.3
tags: 
    - blogging
    - portfolio
    - freelancer
description: "This is a Bootstrap 4.1.3 Boilerplate with Sass, concatenation, minification, autoprefixer, html blocks replacer, sourcemaps, browser-sync, git and gulp task runner."
image: /assets/img/themes/bootstrap-boilerplate.jpg
githubslug: bootstrap-4-boilerplate
---

# This is the basic Bootstrap 4.1.3 template for developers, a Bootstrap template starter for any Bootstrap 4.1.3 project. It uses Sass & Gulp for rapid development.

## What it does
- 'concatScripts'
- 'compileSass'
- 'minifyScripts'
- 'minifyCss'
- 'build'

## How to

**Install**
- `npm install`

**Run**
- `gulp serve`

**Production**
- `gulp`

## Uses `gulp-html-replace` for fast development
If you're building a template this is ideal for you. You can rapidly create blocks of files so you won't need to update them in each page.

Put some blocks in your HTML file:

```
<!-- build:<name> -->
Everything here will be replaced
<!-- endbuild -->
```

Name is the name of the block. Examples:

```
<!-- build:css -->
<link rel="stylesheet" href="assets/css/main.css">
<!-- endbuild -->
```

or this

```
<!-- build:js -->
<script src="assets/js/main.js"></script>
<!-- endbuild -->
```