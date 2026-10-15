# Avenex · Animated Landing Page

A responsive single-page experience built around video, typography, and scroll-driven motion. The project explores how React components and GSAP timelines can create a cohesive visual narrative.

**React 19 · Vite · GSAP · Tailwind CSS**

[Live demo](https://avenex.vercel.app/) · [Portfolio](https://github.com/kuvlay)

## What is implemented

- A video hero with interactive preview transitions.
- Scroll-triggered animations and animated section titles.
- Responsive navigation and reusable buttons.
- About, feature, story, contact, and footer sections.
- Local image, video, audio, and font assets.

## Run locally

With Node.js and npm installed:

```bash
git clone https://github.com/kuvlay/Avenex.git
cd Avenex
npm ci
npm run dev
```

Open the local address printed by Vite. No environment variables or backend services are required by the current source.

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Generate the production frontend bundle |
| `npm run preview` | Preview the built bundle locally |
| `npm run lint` | Run the configured ESLint checks |

## Project structure

`src/App.jsx` composes the page. `src/components/` contains the section and interaction components; `public/` holds media assets.

## Scope and status

This is a frontend interaction study. Contact and promotional controls are presentation elements; no account system, checkout, or message-submission backend is implemented. The existing demo returned a successful HTTP response during review. A fresh local build and interaction/accessibility checks have not been run as part of this documentation update.

<details>
<summary>Credits and project history</summary>

Source lineage: [aarish-io/Avenex](https://github.com/aarish-io/Avenex). Original contributor history and asset files are retained. No standalone license was present in the reviewed source.

</details>
