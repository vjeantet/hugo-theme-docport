+++
title = "Extra menu entries"
date = "2017-04-29T18:36:24+02:00"
Weight=2
+++

You can define additional menu entries in the top navigation menu.

Edit the website configuration `config.toml` and add a `[[menu.shortcuts]]` entry for each link your want to add.

Example from the current website.

```toml
	[[menu.shortcuts]]
	name = "<i class='material-icons'>cloud_download</i> Download"
	url = "https://github.com/vjeantet/hugo-theme-docport/archive/master.zip"
	weight = 11

	[[menu.shortcuts]]
	name = "Hugo Documentation"
	identifier = "hugodoc"
	url = "https://gohugo.io/"
	weight = 20

	[[menu.shortcuts]]
	name = "Credits"
	url = "/credits"
	weight = 30
``

[{{%icon circle-arrow-right%}} Read more about hugo and menu here](https://gohugo.io/extras/menus/)