---
layout: post
title: a post with bibliography
date: 2023-07-12 09:56:00-0400
description: an example of a blog post with bibliography
tags: formatting bib
categories: sample-posts
giscus_comments: true
related_posts: false
---

This post shows how to add bibliography to blog posts. Since GitHub Pages doesn't support the jekyll-scholar plugin, here are some alternative approaches:

## Option 1: Inline Citations
Use standard Markdown links for citations:

```markdown
This is a reference to a paper [1].

## References
1. Einstein, A. (1905). On the Electrodynamics of Moving Bodies. *Annalen der Physik*, 17(10), 891-921.
```

## Option 2: Use a Reference Manager
1. Export your references as HTML from Zotero, Mendeley, etc.
2. Copy the formatted references into your post
3. Link to them using standard Markdown links

## Option 3: Use a Third-Party Service
Services like [ZoteroBib](https://zbib.org/) can generate formatted citations that you can copy into your posts.

## Example Citation
Here's an example of a formatted citation:

> Einstein, A. (1905). On the Electrodynamics of Moving Bodies. *Annalen der Physik*, 17(10), 891-921.

If you need more advanced bibliography features, consider using a static site generator that supports them or hosting your site elsewhere with more plugin support.

For more academic formatting, check the [distill style post](/2018/12/22/distill.html).
