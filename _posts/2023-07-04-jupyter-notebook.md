---
layout: post
title: a post with jupyter notebook
date: 2023-07-04 08:57:00-0400
description: an example of a blog post with jupyter notebook
tags: formatting jupyter
categories: sample-posts
giscus_comments: true
related_posts: false
---

To include a Jupyter notebook in a post, you would typically use the Jekyll Jupyter Notebook plugin. However, since this requires additional plugins not supported by GitHub Pages, we'll need to take a different approach.

### Option 1: Convert to Markdown
1. Export your Jupyter notebook to Markdown using `File > Download as > Markdown (.md)`
2. Copy the Markdown content into your post
3. Add any necessary images to your assets folder

### Option 2: Embed with HTML
You can also embed a Jupyter notebook using an iframe (if you've hosted the notebook elsewhere):

```html
<iframe 
  src="URL_TO_YOUR_NOTEBOOK"
  width="100%" 
  height="400" 
  frameborder="0" 
  allowfullscreen>
</iframe>
```

### Option 3: Use Jupyter's nbviewer
1. Upload your notebook to a public repository
2. Use nbviewer to render it
3. Link to it like this:

```markdown
[View this notebook on nbviewer](https://nbviewer.jupyter.org/URL_TO_YOUR_NOTEBOOK)
```

### Note on Local Development
If you're developing locally and want to use the Jupyter Notebook plugin, you'll need to:
1. Add the `jekyll-jupyter-notebook` gem to your Gemfile
2. Add it to your `_config.yml` plugins
3. Run `bundle install`

However, remember that this setup won't work on GitHub Pages due to plugin restrictions.
