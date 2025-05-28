---
title: "My Second Blog Post"
date: 2025-05-28
---

This is my **Second blog post** on GitHub Pages!

You can write your content here in Markdown format.

# Nobelium
A static blog build on top of Notion and Nextjs, deployed on Vercel.

![Nobelium Screenshot](https://github.com/craigary/nobelium/blob/main/desktop.png?raw=true)

Demo: [https://nobelium.vercel.app/](https://nobelium.vercel.app/)

## Highlights ✨

### 🚀 Fast and responsive
- Fast page render and responsive design
- Fast static generation with efficient compiler

### 🤖 Deploy instantly
- Deploy on Vercel in minutes
- Incremental regeneration and no need to redeploy after update the content in notion

### 🚙 Fully functional
- Comments, full width page, quick search and tag filter
- RSS, analytics, web vital... and much more

### 🎨 Easy for customization
- Rich config options, support English & Chinese interface
- Built with Tailwind CSS, easy for customization

### 🕸 Pretty URLs and SEO friendly

## Quick Start
1. Star this repo 😉
2. Duplicate this Notion template, and share it to the public
3. Fork this project
4. Customize blog.config.js
5. (Optional) Replace favicon.svg, and favicon.ico in /public folder with your own
6. Deploy on Vercel, set following environment variables：
   - NOTION_PAGE_ID (Required): The ID of the Notion page you previously shared to the web, usually has 32 digits after your workspace address
   - NOTION_ACCESS_TOKEN (Optional, not recommended): If you decide not to share your database, you can use token to let Nobelium grab data from Notion database. You can find it in your browser cookies called token_v2

> Keep in mind Notion token is only valid for 180 days, make sure to update manually in vercel dashboard, we probably switch to Official API to resolve this issue in the future. Also, images in Notion database will not properly rendered

That's it! Easy-peasy?

## Play With Docker
Unofficial, thanks to @Vaayne's work!

### Build Docker image yourself