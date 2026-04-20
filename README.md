# cugblbs.github.io

Source code for [ZhuDong's Blog](https://zhudong.site), a personal blog powered by Jekyll and deployed with GitHub Pages.

[中文说明](./README.zh.md)

## Overview

- Personal blog repository for posts, pages, assets, and theme customizations
- Based on the Hux Blog structure and customized for `zhudong.site`
- Supports blog posts, tag pages, RSS feed generation, and a basic PWA setup

## Tech Stack

- Jekyll
- Liquid templates
- Grunt
- LESS
- Bootstrap
- jQuery
- GitHub Pages

## Local Development

### Prerequisites

- Ruby and RubyGems
- Node.js and npm
- Jekyll with the `jekyll-paginate` plugin

### Install Dependencies

```bash
npm install
gem install jekyll jekyll-paginate
```

### Run Locally

Start the Jekyll dev server:

```bash
jekyll serve
```

If you also want to watch LESS changes and serve the generated `_site` directory with Python 3:

```bash
npm run py3wa
```

## Project Structure

- `_posts/`: blog posts
- `_layouts/`: page and post layouts
- `_includes/`: reusable template partials
- `less/`: editable style sources
- `css/`: compiled styles
- `js/`: frontend scripts
- `img/`: site images and post assets
- `pwa/`: manifest and app icons
- `sw.js`: service worker
- `_config.yml`: site configuration

## Deployment

- The site is configured for GitHub Pages
- `CNAME` stores the custom domain configuration for `zhudong.site`
- Publish changes from the repository default branch after review

## License

This project is distributed under the license included in [LICENSE](./LICENSE).
