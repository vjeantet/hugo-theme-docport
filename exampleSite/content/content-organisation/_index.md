+++
title = "Content Organisation"
description = ""
weight = 20
+++

With **Hugo**, pages are the core of your site. Organize your site like any other Hugo project. **Magic occurs with the nested sections implemention done since v0.22 of hugo (congrats @bep)**.

With docport, **Each content page composes the menu**, they shape the structure of your website.

To link pages to each other, place them in a folders hierarchy

```md
	content
	├── _index.md  <-- homepage
	└── folder-one/
	    ├── _index.md  	<-- used as homepage if content/_index.md does not exists
	    └── folder-one-two/ 	<-- section displayed in left menu
	        ├── _index.md 		<-- section's page 
	        ├── folder-one-two-three-A/	
	        │   ├── _index.md
	        └── folder-one-two-three-B/ 	<- section displayed in left menu
	            ├── _index.md 	<-- section's page 
	            ├── page3BA.md  <-- "subpages"
	            └── page3BB.md  <-- "subpages"

```


{{%alert info %}}
**_index.md** is required in each folder (section) : this is the "page" which define section title, content, etc....

**other.md** files are considered as "subpages"
{{%/alert%}}

### Subpages ⊷

Each other **.md** found in a section folder will be considered "subpages", for example, in the `content-organisation` folder there is 1 _index.md (the one your are currently reading) and 1 more files named "extramenu.md", they appear just under this page's title, look upper.


![agence](subpages.png?height=80px&classes=border,shadow)

### Add header to a menu entry

in the page frontmatter, add a `head` param to insert any HTML code before the menu entry:

example to display a "Hello"

```toml
	+++
	title = "Github repo"
	head ="Hello"
	+++
```

### Order sibling menu/page entries

in your frontmatter add `weight` param with a number to order.

```toml
	+++
	title="My page"
	weight = 4
	+++
```
{{%info%}}add `ordersectionsby = "title"` in your config.toml to order menu entries by title{{%/info%}}

### Hide a menu entry

in your frontmatter add `hidden=true` param.
```toml
	+++
	title="My page"
	hidden = true
	+++
```

### Unfolded menu entry by default

One or more menuentries can be displayed unfolded by default. (like the "Getting start" menu entry  in this website)

in your frontmatter add `alwaysopen=true` param.
example :

```toml
	title = "Getting start"
	description = ""
	weight = 1
	alwaysopen = true
```

### Folder structure and file name

Content organization **is** your `content` folder structure.


### Homepage

Find out how to [customize homepage]({{%relref "create-page/set-your-homepage/_index.md"%}}) 



