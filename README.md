# zillow-like

A starting point for a Zillow-style real estate website, built on the Gatsby default starter.

## What it is

The repository was created for a "Zillow-like" property listing site, but it has not been built out yet. At the moment it is the unmodified Gatsby default starter: a small React site with a home page, a second page, a TypeScript example page, a header, an image component and SEO tags. There are no property listings, search, maps or backend code.

## What it does today

- Serves a home page (`/`), a second page (`/page-2/`), a TypeScript page example (`/using-typescript/`) and a 404 page.
- Builds to plain static files that can be hosted anywhere.
- Needs no API keys or environment variables.

## Tech stack

- Gatsby 2 (static site generator)
- React 16
- GraphQL (used by Gatsby for site data and images)
- Sharp image processing plugins
- Prettier for formatting

## How to run it

You need Node.js (version 12 to 14 is the safest match for Gatsby 2) and npm.

```shell
npm install
npm run develop
```

Then open http://localhost:8000.

## Static build (for a live demo)

```shell
npm run build
npm run serve
```

The build writes plain static files to `public/`. Upload the contents of `public/` to any static host (GitHub Pages, Netlify, Vercel, S3). Serve `serve` locally at http://localhost:9000 to check the result.

Other scripts: `npm run clean` clears the Gatsby cache, and `npm run format` runs Prettier. There are no tests (`npm test` is the starter placeholder and exits with an error).

## Status

Prototype. It is only the starter template, and the real estate features are not implemented.

## Credits

Based on [gatsby-starter-default](https://github.com/gatsbyjs/gatsby-starter-default) by Kyle Mathews and the Gatsby team, released under the 0BSD license (see `LICENSE`).
