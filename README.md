# Chiri 🌸

Chiri is a minimal blog theme built with [Astro](https://astro.build), offering customization options while preserving its clean aesthetic.

**Note:** This is a fork of the **[original project](https://github.com/the3ash/astro-chiri)** so that it can be deployed on Cloudflare Workers.

Check the [demo](https://astro-chiri.umemiya.workers.dev) for more details.

![screenshot-light](public/screenshots/screenshot-light.png)
![screenshot-dark](public/screenshots/screenshot-dark.png)


## Features

- [x] Build with Astro
- [x] Responsive
- [x] Light / Dark mode
- [x] MDX
- [x] KaTeX
- [x] Sitemap
- [x] OpenGraph
- [x] RSS
- [ ] Pagination

## Getting Started

1. Fork this repository.

2. Run the following commands:

   ```bash
   git clone <your-repo-url>

   cd <your-repo-name>

   pnpm install

   pnpm dev
   ```

3. Edit `src/config.ts` and `src/content/about/about.md` to your liking.

4. Use `pnpm new <title>` to create new posts, or add your posts to `src/content/posts`.

5. This version of Chiri has a preset Cloudflare Worker adapter. 

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/umehina/astro-chiri-cloudflare)


## Commands

- `pnpm new <title>` - Create a new post (use `_title` for drafts)

## References

- https://paco.me/
- https://benji.org/
- https://shud.in/
- https://retypeset.radishzz.cc/

## License

MIT
