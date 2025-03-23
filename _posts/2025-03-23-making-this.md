---
layout: post
title:  "Starting a portfolio in Jekyll!"
date:   2025-03-23 14:15:31
categories: jekyll update
tags: update
---
For long I looked for a way to publish my software developer thoughts online. I wanted something that was:

- Free
- Easy to use
- Support RSS
- Extendable

and as you might imagine, I found it here, on [GitHub Pages](https://pages.github.com) and [Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) . It fill all the boxes, while providing an environment that supports [Markdown](https://www.markdownguide.org) . I already habituated in using it, so it was a perfect match.

Jekyll starts with a default theme, [Minima](https://github.com/jekyll/minima) that I decided to stick with for a while, so I can extend it and customize it for my needs. One of which, I wanted to extend it with my [Itch.io](https://fredev-k.itch.io) but it doesn't support it by default. Thankfully, I found this [article](https://blog.jakelee.co.uk/adding-new-social-media-link-to-minima/) by Jake Lee that provides a solution to do so.

In case the article becomes unavailable, in sum, what I have done was:

- SVG data must be resized to 16 px, I used a converter online
- Extract the desired icon SVG data
- Insert into assets/minima-social-icons.svg file. It's a plain file, so you can edit with any text editor
- It must follow the file format, include into a symbol with correct ID
- Edit the default footer to include the corresponding social

I'm still not 100% sure if all these steps are needed, for example, the resizing I was hoping the theme to do it for me automatically. However, when attempting without it, the svg wouldn't be displayed in the page. As I use the tech more, I'm hoping to optimize this process in the future.

Stay tuned for updates! Any feedback is appreciated.

Fred,