+++
title = "DocPort Theme for Hugo"
description = ""
weight = 1
+++

[DocPort](https://github.com/vjeantet/hugo-theme-docport), a professional documentation theme built for Hugo. \
It provides a simple navigation, automatic search engine, a high level of configuration and a bunch of shortcodes crafted for documentation (attachment, presentations, child pages, notice, alerts, diagrams...).

	

{{%notice%}}DocPort works with a "page tree structure" to organize content : All contents are pages, which belong to other pages. [read more about this]({{%relref "content-and-customization"%}}).  {{%/notice%}}

## Main features

* [Search Engine]({{%relref "content-and-customization/02-navigation-search/search" %}})
* **Unlimited menu levels**, [subpages]({{%relref "content-and-customization/00-adding-content/#subpages"%}})
* [Placeholders]({{%relref "content-and-customization/02-navigation-search/" %}}) to inject HTML, CSS, JS in theme without modifying it.
* Responsive, [Customizable look and feel, colors]({{%relref "content-and-customization/03-look-and-feel/colors/" %}})
* [RevealJS presentation]({{%relref "content-and-customization/00-adding-content/page-slide/"%}}) from markdown (embededed or fullscreen page)
* [Image resizing, shadow...]({{%relref "content-and-customization/00-adding-content/page-images/" %}})
* A bunch of shortcodes
	* [Mermaid diagram]({{%relref "shortcodes/mermaid/_index.md" %}}) (flowchart, sequence, gantt)
	* [Attachments files]({{%relref "shortcodes/attachments/_index.md" %}}), [Icons]({{%relref "shortcodes/icon/_index.md" %}}), [Buttons]({{%relref "shortcodes/button/_index.md" %}}), [Alerts]({{%relref "shortcodes/alert/_index.md" %}}), [Panels]({{%relref "shortcodes/panel/_index.md" %}}), [Tip/Note/Info/Warning boxes]({{%relref "shortcodes/notice/_index.md" %}}), [Expand]({{%relref "shortcodes/expand/_index.md" %}}), [List child pages]({{%relref "shortcodes/children/_index.md" %}})
	* [Excerpt]({{%relref "shortcodes/excerpt/_index.md"%}}) ! Include segment of content from one page in another
	* [columns]({{%relref "shortcodes/columns/_index.md"%}}), [tabs]({{%relref "shortcodes/tabs/_index.md"%}})


## Contribute to this documentation
Feel free to open issue, pull request ...\
{{%alert%}}Your modification will be deployed automatically when merged in git repo!{{%/alert%}}


## Documentation website
This current documentation has been statically generated with Hugo with a simple command : `hugo -t docport` -- source code is [available here at GitHub](https://github.com/vjeantet/hugo-theme-docPort).

## Static + content management
I author this current documentation via Netlify CMS.\
Docport theme seamless works with [Netlify CMS](https://www.netlifycms.org/)


