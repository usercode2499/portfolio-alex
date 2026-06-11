# Portfolio Website

Personal portfolio for Alexander A. Bongo Jr — Web Developer & AI Researcher.

## Technologies

| Tech | Purpose |
|------|---------|
| Vue 3 (Composition API) | Core framework with `<script setup>` syntax throughout |
| Vite | Build tool and dev server |
| Tailwind CSS | Utility-first styling with custom configuration |
| GSAP + ScrollTrigger | Scroll-based animations and page transitions |
| Lottie | Lightweight motion graphics |
| Netlify | Hosting and deployment |

## Features

- **Scroll-triggered animations** — each section animates into view using GSAP + ScrollTrigger, lazy-loaded so off-screen sections don't initialize unnecessarily
- **Custom mobile navigation** — hamburger menu with circular expansion animation
- **Responsive across devices** — implemented with mobile/tablet/desktop breakpoints and adaptive layout behavior
- **Section-based architecture** — each part of the site is its own Vue component, easy to maintain and extend

## Run locally

```bash
npm install
npm run dev
```
