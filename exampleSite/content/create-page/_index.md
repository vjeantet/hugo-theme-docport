---
post: 👋
lastmodifierdisplayname: Valere JEANTET
title: Create Page
description: Create page
date: 2017-04-24T18:36:24+02:00
layout: ""
hidden: false
head: ""
creatordisplayname: Valere JEANTET
pre: ""
lastmodifieremail: valere.jeantet@gmail.com
creatoremail: valere.jeantet@gmail.com
weight: 10
tags:
  - tag1
  - tag2
---


Hugo-theme-docport uses two types of pages. _Default_ and [_Slide_]({{%relref "create-page/page-slide/_index.md"%}}).

## Page params
Each page may define a Front Matter in yaml, toml or json.

Hugo-theme-docport uses the following parameters on top of the existing ones :

```toml
+++
title="Create Page"

subpage = false # When a page is a subpage, it will be displayed bellow the parent page title, and not in the left menu


# Ajust layout for your page
hide_header=false # set true to hide site header
hide_nav=false # set true to hide the left navigation menu
hide_breadcrumb=false # set true to hide the breadcrumb
hide_toc=false # set true to hide the right menu (table of contents)
hide_footer=false #set true to hide the website footer
+++
```



## Ordering

Hugo provides a flexible way to handle order for your pages.

The simplest way is to use `weight` parameter in the front matter of your page. 

```toml
+++
weight = 10
+++
```

[{{%icon play_circle_filled%}}Read more on content organization]({{%relref "content-organisation/_index.md"%}})





