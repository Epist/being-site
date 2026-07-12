# being.love

The belove website — built with [Astro](https://astro.build), deployed to GitHub Pages.

## How it works

- Pages live in `src/pages/` (each `.astro` file becomes a page on the site)
- The shared page shell (head tags, background, analytics) is `src/layouts/Base.astro`
- Site-wide styles are in `src/styles/global.css`
- Files in `public/` (images, fonts, favicons) are served as-is at the site root

## Publishing

Pushing to `main` automatically builds and deploys the site via GitHub Actions.
It's live at https://www.being.love a minute or two later.

## Local development

```
npm install
npm run dev
```

Then open http://localhost:4321. Changes appear live as files are saved.
