# Ruilong Ren Homepage

Astro-powered personal site for [xiaolong-rrl.github.io](https://xiaolong-rrl.github.io/).

## Sections

- `/` — academic homepage
- `/blog` — technical blog (`src/content/blog/*.md`)
- `/reading` — reading notes (`src/content/reading/*.md`)
- `/finance` — finance learning notes (`src/content/finance/*.md`)

## Local development

```bash
export PATH="$HOME/.local/node/bin:$PATH"   # if using the local Node install
npm install
npm run dev
```

## Write a post

Create `src/content/blog/my-first-post.md`:

```md
---
title: My first post
description: A short note
date: 2026-08-04
tags: [notes]
draft: false
---

Hello world.
```

## Deploy

Push to `main`. GitHub Actions builds Astro and deploys to GitHub Pages.

In the repo **Settings → Pages**, set Source to **GitHub Actions** (not "Deploy from a branch").
