---
layout: post
title: "Affiliates - Jekyll Theme for Bloggers"
theme: "Affiliates"
subtitle: "Jekyll Bootstrap Template for Bloggers"          
categories:
    - Jekyll
tags: 
    - blogging
    - masonry
version:
    - Bootstrap 4
html: https://bootstrapstarter.com/bootstrap-templates/template-affiliates-bootstrap-html/
githubslug: affiliates-jekyll-theme
description: "A Jekyll template built with Bootstrap 4 suitable for affiliate marketers."
image: https://wowthemesnet.github.io/affiliates-jekyll-theme/assets/images/theme1.jpg
---

# "Affiliates" is a free Bootstrap Jekyll theme best suitable for marketers

### Features

- Built for Jekyll
- Compatible with Github pages
- Feed
- Sitemap
- SEO
- Featured Posts
- Index Pagination
- Post Share
- Post Categories
- Prev/Next Link
- Category Archives (this is not yet compatible with github pages though)
- Jumbotron Categories
- Integrations:
    - Disqus Comments
    - Google Analaytics
    - Mailchimp Integration
    - Formspree.io Contact
    - ShareThis Integration
- Design Features:
    - Bootstrap v4.0.0-alpha.6
    - Font Awesome
    - Masonry
- Layouts:
    - Default
    - Post
    - Page
    - Archive
    
### How to Use

If you aren't familiar with Jekyll yet, you should know that it is a static site generator. It will transform your plain text into static websites and blogs. No more databases, slow loading websites, risk of being hacked...just your content. And not only that, with Jekyll you get free hosting with GitHub Pages! This page itself is free hosted on Github with the help of Jekyll and Affiliates template that you're currently previewing. If you are a beginner we recommend you start with [Jekyll's Docs](https://jekyllrb.com/docs/installation/). Now if you know how to use Jekyll, let's move on to using Affiliates template in Jekyll:

### Using Affiliates template with Jekyll

- `git clone https://github.com/wowthemesnet/affiliates-jekyll-theme.git`
- `cd affiliates-jekyll-theme`
- `bundle`
- Edit `_config.yml`. If your site is in root: `baseurl: '/'`. Also, change your Google Analytics code, Disqus username, Authors, Mailchimp, ShareThis code etc.
- `jekyll serve --watch`
- Start blogging by adding your .md files in `_posts`. 

- YAML front matter
    - post featured - `featured:true`
    - post featured image - `image: assets/images/mypic.jpg`
    - page comments - `comments:true`
    - meta description (optional) - `description: "this is my meta description"`
    
YAML Post Example:
```
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
featured: true
---
```

YAML Page Example
```
---
layout: page
title: Affiliates Template for Jekyll
comments: true
---
```
