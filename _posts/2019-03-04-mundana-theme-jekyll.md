---
layout: post
title: "Mundana - Free Jekyll Theme"
theme: "Mundana"
subtitle: "Jekyll Bootstrap Theme"          
categories:
    - Jekyll
tags: 
    - blogging
    - portfolio
    - freelancer
    - full-websites
    - photography
version:
    - Bootstrap 4.1.3
wp: https://www.wowthemes.net/themes/mundana-wordpress/
html: https://bootstrapstarter.com/bootstrap-templates/template-mundana-bootstrap-html/
ghost: https://www.wowthemes.net/themes/mundana-ghost/
description: "A Jekyll template built with Bootstrap 4 suitable for bloggers. Highly inspired by Medium's website layout."
image: https://wowthemesnet.github.io/mundana-theme-jekyll/assets/images/screenshot.jpg
---

# Mundana, a free Bootstrap Jekyll theme for blogging

### Install Mundana

- [Download](https://github.com/wowthemesnet/mundana-theme-jekyll/archive/master.zip) or `git clone https://github.com/wowthemesnet/mundana-theme-jekyll.git`
- In Mundana's newly created directory `bundle`
- Change your configuration in `_config.yml`. If your site is in root, for `baseurl`, make sure this is set to `baseurl: ''`
- `jekyll serve --watch`

### Use

**YAML Post Example**:

```
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Jekyll, tutorial ]
image: assets/images/5.jpg
---
```

`comments: false` - disable comments in posts

`image: "https://www.myexternal.com/image.jpg"`  - set external featured image

`tags: [featured]` - to display Featured posts on homepage


**YAML Page Example**:

```
---
title: "About"
permalink: "/about.html"
image: "/assets/images/screenshot.jpg"
---
```

**Add sticky post on homepage**

Tag a post as `sticky` to highlight a post on homepage.

*Example:*

```
---
layout: post
title:  "Could we reinvent the charm of old cities"
author: jane
categories: [ Jekyll, tutorial ]
image: assets/images/home.jpg
tags: [sticky]
---
```

*Frontend output:*

![mundana jekyll highlight post on homepage](https://user-images.githubusercontent.com/5597992/55400599-f657ac00-5556-11e9-9d9f-7d6e7fa9b0e8.png)
