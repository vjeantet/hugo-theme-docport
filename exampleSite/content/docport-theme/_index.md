+++
title = "DocPort Theme for Hugo"
description = ""
weight = 1
+++

[Hugo-theme-docport](https://github.com/vjeantet/hugo-theme-docport) is a theme for Hugo, a fast and modern static website engine. Hugo is often used for blogs.

**This theme is fully designed for documentation.** and a port of the [docDock theme](https://github.com/vjenatet/hugo-theme-docdock) itslef a fork of a great theme : [hugo-theme-learn from matCornic](https://github.com/matcornic/hugo-theme-learn)

{{%panel%}}DocPort works with a "page tree structure" to organize content : All contents are pages, which belong to other pages. [read more about this]({{%relref "content-organisation/_index.md"%}}) {{%/panel%}}

## Main features


* [Search Engine]({{%relref "search/_index.md" %}})
* **Unlimited menu levels**
* [Placeholders]({{%relref "content-organisation/placeholders/_index.md" %}}) to inject HTML, CSS, JS in theme without modifying it.
* [Customizable look and feel, colors]({{%relref "content-organisation/customize-style/_index.md" %}})
* [RevealJS presentation]({{%relref "page-slide/_index.md"%}}) from markdown (embededed or fullscreen page)
* [Image resizing, shadow...]({{%relref "create-page/page-images/_index.md" %}})
* [Mermaid diagram]({{%relref "shortcodes/mermaid/_index.md" %}}) (flowchart, sequence, gantt)
* [Attachments files]({{%relref "shortcodes/attachments/_index.md" %}}), [Icons]({{%relref "shortcodes/icon/_index.md" %}}), [Buttons]({{%relref "shortcodes/button/_index.md" %}}), [Alerts]({{%relref "shortcodes/alert/_index.md" %}}), [Panels]({{%relref "shortcodes/panel/_index.md" %}}), [Tip/Note/Info/Warning boxes]({{%relref "shortcodes/notice/_index.md" %}}), [Expand]({{%relref "shortcodes/expand/_index.md" %}}), [List child pages]({{%relref "shortcodes/children/_index.md" %}})
* [Excerpt]({{%relref "shortcodes/excerpt/_index.md"%}}) ! Include segment of content from one page in another

## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it
{{%alert%}}Your modification will be deployed automatically when merged !{{%/alert%}}


## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t docport` -- source code is [available here at GitHub](https://github.com/vjeantet/hugo-theme-docPort)

