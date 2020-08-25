+++
title="Navigation entries"
pre = "👻&nbsp;&nbsp;"
post = "&nbsp;&nbsp;👋"
subpage = true
hidden = false
weight = 300
+++

Each page is displayed on navigation bars
* _index.md files are displayed on the left menu
* other files are displayed as subpages (like this one) bellow the section title.


You can control how they are displayed thanks to page FrontMatter.

Hugo-theme-docport uses the following parameters to acheive this :

```toml
+++
# Hide this page from navigation
hidden = false


# Display before and after in navigations menus surrounding page's title
pre = "👻"
post = "👋"

# LEFT MENU ONLY (Sections)
# as an exemple, on the Getting started Page a head="<hr/>" is set
head = "<hr/>"

# Menu opened by default (like the Getting started menu entry)
alwaysopen = false

+++
```