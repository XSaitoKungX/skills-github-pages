---
layout: post
title: "My First GitHub Pages Post"
date: 2026-09-17
description: My first blog post while learning how GitHub Pages and Jekyll handle posts.
---

# My First GitHub Pages Post

This is my first post created with **Jekyll** and **GitHub Pages**.

The goal of this post is to understand how Jekyll handles blog content inside the `_posts` directory.

## What I learned

Jekyll automatically detects posts stored inside the `_posts` directory as long as they follow the expected filename format:

```text
YYYY-MM-DD-title.md
````

For example:

```text
2026-09-17-my-first-github-pages-post.md
```

The date in the filename helps Jekyll determine when the post was published.

## Front Matter

Each post starts with YAML Front Matter:

```yml
---
layout: post
title: "My First GitHub Pages Post"
date: 2026-09-17
---
```

This metadata tells Jekyll how the post should be rendered and provides information such as the title and publication date.

## Markdown Content

The actual content of the post can then be written using Markdown.

That includes:

* Headings
* Lists
* Links
* Images
* Code blocks
* Quotes
* Tables
* Inline code

## Why this matters

Posts make it possible to use GitHub Pages not only as a static homepage, but also as a simple blog or documentation site.

Each new Markdown file can become its own published page automatically.

## Next steps

* Post categories
* Tags
* Custom layouts
* Post navigation
* Excerpts
* RSS feeds
* Custom styling

---

My first Jekyll post is now live.
