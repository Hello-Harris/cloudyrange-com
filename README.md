# ☁️ Cloudy Range (cloudyrange.com)

Welcome to the repository for **Cloudy Range**, a high-performance personal blog and portfolio website. This project is built using the [Astro Starter Kit: Blog](https://github.com/cloudflare/templates/tree/main/astro-blog-starter-template) and is optimized for deployment on **Cloudflare Pages**.

## 🚀 Overview

Cloudy Range is designed to be a fast, minimalist, and SEO-friendly platform. By leveraging Astro's static site generation and Cloudflare's global network, the site achieves near-instant load times and top-tier performance scores.

## 🛠️ Repository Structure

This project follows the standard Astro directory structure:

```text
├── src/
│   ├── components/   # Reusable UI components
│   ├── layouts/      # Page templates (Blog posts, general pages)
│   ├── pages/        # File-based routing (index, about, etc.)
│   └── content/      # Markdown/MDX blog post collections
├── public/           # Static assets (images, icons, robots.txt)
├── astro.config.mjs  # Astro configuration
└── wrangler.json     # Cloudflare Workers/Pages configuration