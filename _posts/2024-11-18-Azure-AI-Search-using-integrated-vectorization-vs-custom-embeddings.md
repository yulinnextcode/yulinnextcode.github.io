---
layout: post
title: Azure AI Search using integrated vectorization vs custom embeddings
subtitle: Azure AI Search default embeddings
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Yulin Zhao
---

{: .box-success}
This article is to compare using Azure AI Search with integrated vectorization vs. with custom embeddings. The results will be displayed.

## Azure AI Searching using integrated data chunking and embedding



## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.



**Here is some bold text**



## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
