# HryGan404.github.io

Generated static output for a personal Hugo site.

Live site: <https://HryGan404.github.io/>

## About this repository

This repository contains the HTML, CSS, JavaScript, images, feeds, and local
search index served by GitHub Pages.

Generated files should not be edited by hand. Make content or configuration
changes in the site source checkout, then rebuild this repository.

## Update the deployment output

The site output is generated separately. After the output has been regenerated,
update this repository with:

```shell
git add -A
git commit -m "chore: rebuild site"
git push origin main
```

The local search index under `search/` must be committed and pushed together
with the other generated files.

## Generated content

```text
index.html       Home page
posts/           Published article pages
categories/      Category pages
tags/            Tag pages
search/          Client-side local search index
css/             Compiled theme styles
js/              Bundled theme scripts
```
