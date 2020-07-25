+++
title = "Create Page"
description = ""
date = "2017-04-24T18:36:24+02:00"
creatordisplayname = "Valere JEANTET"
creatoremail = "valere.jeantet@gmail.com"
lastmodifierdisplayname = "Valere JEANTET"
lastmodifieremail = "valere.jeantet@gmail.com"
tags = ["tag1","tag2"]
weight = 10

layout = ""
head = "<hr/>MY SECTION"
pre = ""
post = "👋"
hidden = false

+++


Hugo-theme-docport defines two types of pages. _Default_ and _Slide_.

## Page layout
Each page may define a Front Matter in yaml, toml or json.

Hugo-theme-docport uses the following parameters on top of the existing ones :

```toml
+++
title="Create Page"
layout = "full"
# - <empty> will show left navigation, table of content, breadcrumb 
# - "simple" - will hide right bar and breadcrumb 
# - "full" will hide left nav, right nav and breadcrumb
# - "raw" - only the page content will display (usefull for homepage)
#
# other keys exists to control how to render this page in navigations (see "Navigation Appearance")
#
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

## Page as a slidedeck
* **Slide** is a page that use the full screen to display its markdown content as a [reveals.js presentation](http://lab.hakim.se/reveal-js/).

To tell Hugo-theme-docport to consider a page as a slide, just add a `type="slide"`in then frontmatter of your file. [{{%icon play_circle_filled%}}read more on page as slide]({{%relref "page-slide.md"%}})

```toml
+++
type="slide"
+++
```



