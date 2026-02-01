# CLAUDE.md

This file provides guidance for Claude Code when working with this repository.

## Project Overview

This is Karan Sampath's personal website (karansampath.com), built with Hugo static site generator and the Archie theme. The site is deployed via GitHub Pages.

## Tech Stack

- **Static Site Generator**: Hugo (v0.153.4)
- **Theme**: Archie (`themes/archie/`)
- **Deployment**: GitHub Pages via GitHub Actions
- **Domain**: karansampath.com

## Project Structure

```
├── config.toml          # Hugo site configuration
├── content/             # Markdown content files
│   ├── _index.md        # Homepage content
│   ├── about.md         # About page
│   ├── blog/            # Blog posts
│   ├── projects.md      # Projects page
│   ├── interests.md     # Interests page
│   └── pages/           # Additional pages (hiking, moviegoer)
├── static/images/       # Static image assets
├── themes/archie/       # Hugo theme
└── .github/workflows/   # GitHub Actions for deployment
```

## Common Commands

```bash
# Run local development server
hugo server -D

# Build the site (output to ./public)
hugo

# Build with minification (production)
hugo --gc --minify
```

## Content Management

- All content is written in Markdown files in the `content/` directory
- Blog posts go in `content/blog/` with front matter including title and date
- Static images are stored in `static/images/`
- Front matter uses TOML format (between `---` delimiters)

## Deployment

- Pushes to `main` branch automatically trigger deployment via GitHub Actions
- The workflow (`.github/workflows/hugo.yaml`) builds with Hugo and deploys to GitHub Pages
- Build artifacts are uploaded to the `public/` directory

## Configuration

Key settings in `config.toml`:
- `baseurl`: https://www.karansampath.com
- `theme`: archie
- `mode`: toggle (light/dark theme support)
- Social links configured under `[[params.social]]`
- Navigation menu under `[[menu.main]]`
