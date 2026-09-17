---
title: Learning GitHub Pages
description: A hands-on learning project for GitHub Pages, Jekyll, Markdown, and static site deployment.
---

# Learning GitHub Pages

> A hands-on project for learning how to build, configure, and publish a static website with **GitHub Pages**.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-2ea44f?logo=github)](https://xsaitokungx.github.io/skills-github-pages/)
![Jekyll](https://img.shields.io/badge/Jekyll-Powered-CC0000?logo=jekyll&logoColor=white)
![GitHub Skills](https://img.shields.io/badge/GitHub-Skills-181717?logo=github)

---

## About this project

This repository started as part of the **GitHub Skills: GitHub Pages** exercise.

The goal was to learn the fundamentals of publishing a website directly from a GitHub repository and understand how **GitHub Pages**, **Jekyll**, **Markdown**, and repository-based deployment work together.

Instead of stopping after completing the exercise, this site also serves as a small playground for experimenting with GitHub Pages features.

## What I learned

Through this project, I learned how to:

- Enable GitHub Pages for a repository
- Deploy a website directly from a Git branch
- Build pages using Markdown
- Use YAML Front Matter
- Configure Jekyll through `_config.yml`
- Apply and configure a Jekyll theme
- Work with GitHub Pages URLs and project paths
- Use commits to trigger automatic deployments
- Configure metadata and site information
- Extend a basic GitHub Pages site beyond the initial exercise

## How it works

The basic workflow behind this site is simple:

```text
Edit files
    ↓
Commit changes
    ↓
Push to main
    ↓
GitHub Pages builds the site
    ↓
Website is deployed
````

The homepage itself is written in `index.md`, while global site configuration is stored in `_config.yml`.

GitHub Pages uses **Jekyll** to transform the repository content into the final static website.

## Project structure

```text
skills-github-pages/
├── .github/
├── _config.yml
├── index.md
├── README.md
└── LICENSE
```

### `index.md`

Contains the content of this homepage.

### `_config.yml`

Contains global Jekyll and GitHub Pages configuration such as the site title, description, theme, plugins, and URL settings.

### `.github/`

Contains files used by the GitHub Skills exercise and GitHub automation.

---

## Exercise progress

| Step                                | Status |
| ----------------------------------- | :----: |
| Create the repository               |    ✅   |
| Enable GitHub Pages                 |    ✅   |
| Create the homepage                 |    ✅   |
| Configure Jekyll                    |    ✅   |
| Customize the site                  |    ✅   |
| Complete the GitHub Skills exercise |    ✅   |

**Exercise completed.**

The repository remains available as a reference and playground for further GitHub Pages experiments.

## Technologies

`GitHub Pages` · `Jekyll` · `Markdown` · `YAML` · `Git` · `GitHub Actions`

## What's next?

Although the original GitHub Skills exercise is complete, there is still plenty to explore:

* Custom layouts
* Additional pages
* Blog posts with `_posts`
* Custom SCSS/CSS
* Navigation
* SEO metadata
* Open Graph metadata
* Sitemap and RSS feeds
* Custom domains
* GitHub Actions based deployments

---

### Useful links

* [View the live site](https://xsaitokungx.github.io/skills-github-pages/)
* [View the repository](https://github.com/XSaitoKungX/skills-github-pages)
* [GitHub Pages documentation](https://docs.github.com/pages)
* [Jekyll documentation](https://jekyllrb.com/docs/)

---

<sub>Built while learning GitHub Pages, Jekyll, and static site deployment.</sub>
