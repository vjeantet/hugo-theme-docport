+++
title="Create homepage"
+++



{{% alert theme="success" %}}By default, this theme use the first section (folder) available in your content folder as a homepage.{{%/alert%}}

## Create a dedicated homepage
To tell Hugo-theme-docport to consider a page as homepage's content, just create a content file named `_index.md` in `content` root folder.
* use `hide_header`,`hide_nav`,`hide_breadcrumb`,`hide_toc`,`hide_footer` params in frontmatter to control what to show/hide for this page

## Use plain HTML for your homepage
set a `layout=raw` param in frontmatter, your content will render without any navigation, menu, header, footer.


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

