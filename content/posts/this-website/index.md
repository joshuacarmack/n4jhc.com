---
title: "How I Made This Website"
date: 2025-08-01
draft: false
summary: "I wanted to learn more about Hugo, so I built this site in it."
tags: ["development","website","cloudflare","dns","coding","hugo"]
---

## How did I make this website?

This site is built with [Hugo](https://gohugo.io/), a framework for generating static websites. I wanted something simpler than maintaining full WordPress installs for small sites, and Hugo was the answer.

You can install Hugo and run a single command, for example:

```bash
hugo new site joshuacarmack.com
```

That scaffolds the entire site and leaves you ready to edit.

For the design, I used the [Blowfish](https://blowfish.page/) theme. Blowfish has its own tooling that sets up Hugo, the theme, and a starter site in one step:

```bash
blowfish-tools new joshuacarmack.com
```

From there, I customized the homepage to list my projects and adjusted the menu bar. Creating content is as simple as adding a folder inside `content/` and dropping in a Markdown file for a new blog post.

I edit the site a few different ways:
- In VS Code on my desktop
- With Working Copy on my iPad
- Or directly in GitHub’s editor

The full source is available on GitHub: [github.com/joshuacarmack/joshuacarmack.com](https://github.com/joshuacarmack/joshuacarmack.com). You can see every file Hugo builds from and track any changes I’ve made.

The live site is deployed on **Cloudflare Pages**. Whenever I push to the `master` branch, Cloudflare automatically rebuilds the site and publishes updates within minutes.

Because this is a static website, it loads quickly and doesn’t rely on heavy scripts running in the background.

If you want a fast, lightweight way to build websites or blogs, I highly recommend giving Hugo a try.
