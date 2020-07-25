+++
title="Navigation appearance"
pre = "👻&nbsp;&nbsp;"
post = "&nbsp;&nbsp;👋"
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
# Show a "MY SECTION" text before menu entry
# as an exemple, on the Create Page a head="<hr/>" is set
head = "MY SECTION"

# Menu opened by default
alwaysopen = false

+++
```