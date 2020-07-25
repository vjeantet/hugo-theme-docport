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
* [RevealJS presentation]({{%relref "page-slide.md"%}}) from markdown (embededed or fullscreen page)
* [Image resizing, shadow...]({{%relref "create-page/page-images.md" %}})
* [Attachments files]({{%relref "shortcodes/attachments.md" %}})
* [List child pages]({{%relref "shortcodes/children/_index.md" %}})
* [Excerpt]({{%relref "shortcodes/excerpt.md"%}}) ! Include segment of content from one page in another
* [Mermaid diagram]({{%relref "shortcodes/mermaid.md" %}}) (flowchart, sequence, gantt)
* [Icons]({{%relref "shortcodes/icon.md" %}}), [Buttons]({{%relref "shortcodes/button.md" %}}), [Alerts]({{%relref "shortcodes/alert.md" %}}), [Panels]({{%relref "shortcodes/panel.md" %}}), [Tip/Note/Info/Warning boxes]({{%relref "shortcodes/notice.md" %}}), [Expand]({{%relref "shortcodes/expand.md" %}})

## Contribute to this documentation
Feel free to update this content, just click the **Edit this page** link displayed on top right of each page, and pullrequest it
{{%alert%}}Your modification will be deployed automatically when merged !{{%/alert%}}


## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t docport` -- source code is [available here at GitHub](https://github.com/vjeantet/hugo-theme-docPort)

