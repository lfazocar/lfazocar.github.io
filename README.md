# Astro Portfolio

A simple website designed to be a portfolio to showcase the different projects I've worked on.

## How it works

This website is basically a blog that uses markdown files to serve its content.

To create a new project page, simply create a new markdown file with the project info and add these values to the frontmatter:

```yaml
layout: ../../layouts/ProjectLayout.astro
name: string (required)
address: string (optional)
github: string (optional)
description: string (required)
image: (optional)
    url: string (required)
    alt: string (required)
tags: string array (required)
order: integer (required)
```

## To Do

- Tags
- Light and Dark mode toggle
- Implement i18n and spanish version

## Made with

- [Astro](https://astro.build)
- [Pico CSS](https://picocss.com/)
