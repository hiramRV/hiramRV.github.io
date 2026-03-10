# HiramRV GitHub Pages Site

Quick link to the page: [Link](https://hiramrv.github.io)

## Run locally

Prerequisites:
- Ruby and Bundler installed

This repo uses a local Jekyll 4 toolchain for preview on modern Ruby.
GitHub Pages can still host the generated static output.

From the repo root:

```bash
bundle config set --local path 'vendor/bundle'
bundle install
bundle exec jekyll serve --livereload
```

Then open: `http://127.0.0.1:4000`

## Build locally

```bash
bundle exec jekyll build
```
