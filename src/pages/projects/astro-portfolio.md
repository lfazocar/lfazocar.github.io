---
layout: ../../layouts/ProjectLayout.astro
name: 'My Portfolio (This website!)'
address: 'https://lfazocar.github.io/'
github: 'https://github.com/lfazocar/lfazocar.github.io/'
description: "A simple website made with Astro and hosted in GitHub Pages to showcase the projects I've worked on."
tags: ["frontend", "astro"]
order: 0
---

## Welcome!

As the description says, this is a small website to showcase the projects I've worked on.

I'm not exactly a CSS or UI expert so I decided to keep it simple with Pico CSS and small amounts of custom CSS here and there to make the website look the way I want it to.

As for the framework, I chose Astro because after a little bit of research it seemed like the option that best fit my needs. It's light and fast while also having access to integrations in case I want to build something more complex on top of it.

## Features

As I add features to this website I will write a little bit about the thought process and experience while developing them here.

### Tag sorting system for projects
- [ ] Incomplete

Honestly this isn't a priority. I don't have enough project entries for this to be actually helpful.

### Light and Dark mode toggle
- [x] **Done!**

This cute little toggle while simple at first had some unexpected complexity behind it.

Since this website is a <span data-tooltip="Multi-Page Application">MPA</span> I couldn't just change some CSS classes and call it a day, I also had to persist the theme after page changes. I had 2 options: Convert the website into a <span data-tooltip="Single-Page Application">SPA</span> so I don't have to worry about persisting the theme or use `localStorage` to save the theme and then initialize it every time the page changes.

I tried the SPA approach at first but I feel it goes against what I'm trying to do with this website (and it also broke more things than it fixed), so in the end I went with `localStorage`.

### cURL HTTP command generator
- [x] **Done!**

This tool exists because I'd rather use cURL over Postman for quickly testing one or two endpoints, since it allows me to stay in the terminal with no need to open a separate application.

Originally I wanted to make this a CLI tool but I figured that since it's a simple script I might as well upload it here and create an interactive frontend for it. It's also a good opportunity to do some coding with vanilla JS.
