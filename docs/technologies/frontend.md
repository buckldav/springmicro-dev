---
layout: default
title: Frontend
parent: Technologies
nav_order: 2
---

# Frontend

## Key Frameworks and Technologies

### [TypeScript](https://www.typescriptlang.org/)

Use TypeScript wherever possible for development.

### [Vite](https://vitejs.dev/)

Vite is a build tool that can be used for vanilla projects and JavaScript frameworks. Use it to transpile and compile your TypeScript and framework code.

### [Next.js](https://nextjs.org/)

Next.js is the full-stack framework built on React.js. Use [NextAuth](https://next-auth.js.org/) to manage a user session. The Bridge is made with Next.js.

### [SvelteKit](https://kit.svelte.dev/)

Use SvelteKit as the full-stack framework for Svelte.js. Use [NextAuth](https://next-auth.js.org/) to manage a user session.

#### SvelteKit vs. Next.js

General tradeoffs (according to David Buckley):

| SvelteKit           | Next.js                   |
| ------------------- | ------------------------- |
| Smaller bundle size | Larger bundle size        |
| Smaller ecosystem   | Robust ecosystem of tools |

In general, if the app requires a lot of functionality in the frontend, it might be prudent to use Next.js because React tools are way more abundant (e.g. MapBox, Component Libraries like MUI, etc.) than the Svelte equivalents. Otherwise, use SvelteKit because of the fast load times and minimal configuration.

## Component Driven Development

Component Driven Development is where atomic components are the basis for UI development. Use these components to build layouts, pages, etc. increasing in complexity from the bottom up.

- Use [Storybook.js](https://storybook.js.org/) for maintaining and demonstrating components and states.

## Internal Tools

- Use [MaterialUI](https://mui.com/) for theming for internal tools.
- Use React and Next.js (with NextAuth) for internal UI portals and dashboards.

## DevOps

Use [Netlify](https://www.netlify.com/) for static site deployment. Use [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) for formatting.
