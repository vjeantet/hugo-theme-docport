+++
title = "Content Organisation"
description = ""
weight = 20
+++

With **Hugo**, pages are the core of your site. Organize your site like any other Hugo project. **Magic occurs with the nested sections implemention done since v0.22 of hugo (congrats @bep)**.

With docport, **Each content page composes the menu**, they shape the structure of your website.

To link pages to each other, place them in a folders hierarchy

```
content
├── _index.md
└── level-one/
    ├── _index.md
    └── level-two/
        ├── _index.md
        ├── level-threeA/
        │   ├── _index.md
        └── level-threeB/
            ├── _index.md
            ├── page3BA.md
            └── page3BB.md

```


{{%alert info %}} **_index.md** is required in each folder, it's your "folder home page"{{%/alert%}}

### Subpages ⊷

Each other **.md** found in folder will be considered "sub pages", for example, in the `content-organisation` folder there is 1 _index.md (the one your are currently reading) and 2 more files named "logo-placeholder.md" and "extramenu.md", they appear just under this page's title, look upper.


![agence](subpages.png?height=80px&classes=border,shadow)

### Add header to a menu entry

in the page frontmatter, add a `head` param to insert any HTML code before the menu entry:

example to display a "Hello"

	+++
	title = "Github repo"
	head ="Hello"
	+++



### Add icon to a menu entry

in the page frontmatter, add a `pre` param to insert any HTML code before the menu label:

example to display a github icon 
```toml
	+++
	title = "Github repo"
	pre ="<i class='material-icons' >create</i> "
	+++
```


### Customize menu entry label

Add a `name` param next to `[menu.main]`

	+++
	[menu.main]
	parent = ""
	identifier = "repo"
	pre ="<i class='material-icons' >create</i> "
	name = "Github repo"
	+++


### Create a page redirector
Add a `url` param next to `[menu.main]`

	+++
	[menu.main]
	parent = "page"
	identifier = "page-images"
	weight = 23
	url = "/shortcode/image/"
	+++

### Order sibling menu/page entries

in your frontmatter add `weight` param with a number to order.

	+++
	title="My page"
	weight = 4
	+++

{{%info%}}add `ordersectionsby = "title"` in your config.toml to order menu entries by title{{%/info%}}


### Hide a menu entry

in your frontmatter add `hidden=true` param.

	+++
	title="My page"
	hidden = true
	+++


### Unfolded menu entry by default

One or more menuentries can be displayed unfolded by default. (like the "Getting start" menu entry  in this website)

in your frontmatter add `alwaysopen=true` param.
example :

```
title = "Getting start"
description = ""
weight = 1
alwaysopen = true
```

### Folder structure and file name

Content organization **is** your `content` folder structure.


### Homepage

Find out how to [customize homepage]({{%relref "homepage.md"%}}) 



