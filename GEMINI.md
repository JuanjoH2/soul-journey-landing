# Project Overview

This is a landing page template built with [Astro](https://astro.build/) and [Tailwind CSS](https://tailwindcss.com/). It's designed to be a starting point for creating fast, modern, and beautiful landing pages.

The project is structured as a typical Astro project:

-   `src/pages` contains the pages of the website.
-   `src/components` contains reusable Astro components.
-   `src/styles` contains the global styles and theme configuration.
-   `src/assets` contains static assets like images.
-   `public` contains static assets that don't need to be processed by Astro.

# Building and Running

The following commands are available to build, run, and test the project:

-   `npm install`: Install dependencies
-   `npm run dev`: Start local dev server at `localhost:4321`
-   `npm run build`: Build your production site to `./dist/`
-   `npm run preview`: Preview your build locally, before deploying
-   `npm run format`: Format code with [Prettier](https://prettier.io/)
-   `npm run clean`: Remove `node_modules` and build output

# Development Conventions

The project uses [Prettier](https://prettier.io/) for code formatting. The configuration is in `.prettierrc.mjs`.

The project also uses [Tailwind CSS](https://tailwindcss.com/) for styling. The configuration is in `tailwind.config.cjs`. The theme is defined in `src/styles/theme.css`.

The project is written in TypeScript. The configuration is in `tsconfig.json`.
