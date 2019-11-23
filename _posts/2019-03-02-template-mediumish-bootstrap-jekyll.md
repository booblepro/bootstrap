---
layout: post
title: "Mediumish - Free Jeyll Theme"
theme: "Mediumish"
subtitle: "Jekyll Bootstrap Theme"          
categories:
    - Jekyll
    - Popular
tags:
    - blogging
    - masonry
version:
    - Bootstrap 4
html: https://bootstrapstarter.com/bootstrap-templates/template-mediumish-bootstrap-html/
wp: https://www.wowthemes.net/themes/mediumish-wordpress/
ghost: https://www.wowthemes.net/themes/mediumish-ghost/
githubslug: mediumish-theme-jekyll
description: "A Jekyll template built with Bootstrap 4 suitable for bloggers. Highly inspired by Medium's website layout."
image: /assets/img/themes/mediumish-jekyll.jpg
---

# "Mediumish" is a free Bootstrap Jekyll theme for blogging, collections, resources, reviews websites

#### Features

*   Built for Jekyll
*   Compatible with Github pages
*   Featured Posts
*   Index Pagination
*   SEO
*   Feed
*   Sitemap
*   Post Share
*   Post Categories
*   Prev/Next Link
*   Category Archives (Compatible with Github pages)
*   Jumbotron Categories
*   Post Reviews with Stars
*   Blurred Spoilers
*   Table of Content
*   Lazy Load Images
*   Integrations:
    *   Disqus Comments
    *   Google Analaytics
    *   Mailchimp Integration
    *   Adsense
*   Design Features:
    *   Bootstrap v4.x
    *   Font Awesome
    *   Masonry
*   Layouts:
    *   Default
    *   Post
    *   Page
    *   Archive
    *   Categories (for 100% compatibility with Github pages)

#### What's Jekyll

If you aren't familiar with Jekyll yet, you should know that it is a static site generator. It will transform your plain text into static websites and blogs. No more databases, slow loading websites, risk of being hacked...just your content. And not only that, with Jekyll you get free hosting with GitHub Pages! This page itself is free hosted on Github with the help of Jekyll and Mediumish template that you're currently previewing. If you are a beginner we recommend you start with [Jekyll's Docs](https://jekyllrb.com/docs/installation/). Now if you know how to use Jekyll, let's move on to using Mediumish template in Jekyll:

#### How to use "Mediumish" theme

1.  [Download](https://github.com/wowthemesnet/mediumish-theme-jekyll/archive/master.zip) or `git clone https://github.com/wowthemesnet/mediumish-theme-jekyll.git`
2.  `cd mediumish-theme-jekyll`
3.  `bundle`
4.  Edit `_config.yml` options. If your site is in root: `baseurl: ''`. Also, change your Google Analytics code, disqus username, authors, Mailchimp list etc.
5.  `jekyll serve --watch`
6.  Start by adding your `.md` files in `_posts`. Mediumish already has a few examples.
7.  YAML front matter
    *   featured post - `featured:true`
    *   exclude featured post from "All stories" loop to avoid duplicated posts - `hidden:true`
    *   post image - `image: assets/images/mypic.jpg`
    *   external post image - `image: "https://externalwebsite.com/image4.jpg"`
    *   page comments - `comments:true`
    *   meta description (optional) - `description: "this is my meta description"`

##### YAML Post Example:

```markdown
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
description: "Something about this post here"
---
```

##### YAML Page Example

```markdown
---
layout: page
title: Mediumish Template for Jekyll
comments: true
---
```

##### Rating

```markdown
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
description: "Something about this post here"
rating: 4.5
---
```

##### Adsense

Enable this option by editing `_config.yml`. 

```markdown
# Adsense (change to "enabled" to activate, also your client id and ad slot. Create a new ad unit from your Adsense account to get the slot.)
adsense: "disabled"
adsense-data-ad-client: "ca-pub-3412143450191416"
adsense-data-ad-slot: "1363087678"
```

##### Lazy Load Images

Enable this option by editing  `_config.yml`. 

```markdown
# Lazy Images ("enabled" or "disabled")
lazyimages: "enabled"
```

##### Table of Contents

Add `toc:true` on your post YAML.

```markdown
---
layout: post
title:  "Education must also train one for quick, resolute and effective thinking."
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/3.jpg
beforetoc: "Markdown editor is a very powerful thing. In this article I'm going to show you what you can actually do with it, some tricks and tips while editing your post."
toc: true
---
```

`beforetoc` adds a paragraph before the TOC is displayed. [Demo](https://wowthemesnet.github.io/mediumish-theme-jekyll/education/)