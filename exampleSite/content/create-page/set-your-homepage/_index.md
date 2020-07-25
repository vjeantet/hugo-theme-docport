+++
title="Create homepage"
+++



{{% alert theme="success" %}}By default, this theme use the first section (folder) available in your content folder as a homepage.{{%/alert%}}

## Create a dedicated homepage
To tell Hugo-theme-docport to consider a page as homepage's content, just create a content file named `_index.md` in `content` root folder.
* use the `layout` key in frontmatter to control what to show/hide for this page

## Get rid of header, footer and navigations for Homepage
with `layout=raw` in frontmatter, your content will render without any navigation, menu, header, footer.



Example
```toml
+++
title="Homepage"
layout="raw"
+++
<div class="myHome">
	Hello
</div>
```

