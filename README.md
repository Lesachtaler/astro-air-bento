# Astro Air Bento

[Astro Theme Details](https://astro.build/themes/details/astro-air-bento/)

A minimalism, personal blog theme for Astro, which inspired by [Astro Air](https://astro-air.guoqi.dev).

> If you find this project helpful, please consider giving it a star ⭐️

[![Built with Astro](https://astro.badg.es/v1/built-with-astro/tiny.svg)](https://astro.build)
[![Netlify Status](https://api.netlify.com/api/v1/badges/a4eb6e88-606d-4ea6-9a53-179e03a7e2ef/deploy-status)](https://app.netlify.com/sites/astro-air-bento/deploys)

<img style="border-radius: 10px;" src="https://cdn.jsdelivr.net/gh/deventw/astro-air-bento@master/public/preview.png" alt="Astro Air Bento">

## Showcase

- [Astro Air Bento](https://astro-air-bento.netlify.app)
- [Astro Air](https://astro-air.guoqi.dev)
- [Guoqi's blog](https://blog.sunguoqi.com)
- ...

> Welcome to add your own blog to the list by creating 🅿🆁

## Features

- [x] 🌓 Dark mode support
- [x] 📱 Fully device responsive
- [x] 🎨 Clean and minimalist design
- [x] 📝 Markdown/MDX for content authoring
- [x] 🏄‍♂️ SSG static rendering, SEO friendly
- [x] 🌐 i18n support (EN/ZH)
- [x] 🔗 Social media integration
- [x] 📰 RSS feed & sitemap support
- [x] 🛠️ Google analysis integration
- [x] 💬 Commenting Integration (Twikoo)
  <!-- - [ ] 🔍 Local search functionality -->
  <!-- - [ ] 🎨 Enhance Transition and Animation -->
  <!-- - [ ] ...and more -->

## Quick Start

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/deventw/astro-air-bento)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/deventw/astro-air-bento)

## Configuration

- Open `src/config/index.ts` and customize your site settings

- Open `src/config/links.ts` and customize your site links

- Open `src/config/zh(en)/about.mdx(intro.mdx、links.mdx)` and customize your pages content

## Writing Content

1. Create new blog posts in the `src/content/posts/` directory
2. Use the following frontmatter template:

```markdown
---
title: "Your Post Title"
description: "A brief description of your post"
pubDate: YYYY-MM-DD
updatedDate(optional): YYYY-MM-DD
tags(optional): ["tag1", "tag2"]
ogImage(optional): "cover image URL"
---

Your content here...
```

## Update Theme

```bash
git remote add upstream https://github.com/deventw/astro-air-bento

git fetch upstream

git merge upstream/main --allow-unrelated-histories

```

## Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create your feature branch
3. Submit a pull request

```bash
git clone https://github.com/deventw/astro-air-bento

cd astro-air-bento

bun install

bun dev
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
