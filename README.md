# STEMSeeds

A responsive website for a student-led STEM education initiative, helping visitors explore hands-on experiment kits, meet the team, and get involved.

**[Visit the website](https://stemseeds.vercel.app)**

## Features

- Animated wordmark, floating photography, and parallax interactions.
- Dedicated pages for STEM kits, the team, the initiative, joining, and donations.
- Experiment descriptions and educational resources.
- Reusable UI components and centralized content configuration.
- Responsive hero layouts and reduced-motion handling.

## Engineering

Built with **Next.js 16, React 19, TypeScript, Tailwind CSS 4, and Motion**.

Page composition lives in `app/`, reusable presentation lives in `components/`, and editable copy and structured data live in `content/`. This lets content updates happen without rewriting the page components.

The home hero uses separate mobile and desktop photo arrangements. It reduces parallax sensitivity when the visitor requests reduced motion, and uses Next.js image components for its photographs.

## Run locally

Install Node.js 22 LTS and npm, then:

```bash
git clone https://github.com/arjunkrishna1784/stemseeds.git
cd stemseeds
npm ci
npm run dev
```

Open [localhost:3000](http://localhost:3000).

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run lint` | Run ESLint |
| `npm run build` | Build for production |
| `npm start` | Serve the production build |

## Where to make changes

| Directory | Contents |
| --- | --- |
| `app/` | Routes, layout, and global styles |
| `components/home/` | Home page sections |
| `components/ui/` | Shared UI and animation components |
| `content/` | Site copy, kit details, team information, and navigation |
| `public/images/` | Photos and visual assets |
| `hooks/`, `lib/` | Shared hooks and utilities |

Start with `content/site.ts` for site configuration, `content/kits.ts` for experiments, and `content/team.ts` for team information.

## Project role

Website development led by **Arjun Krishnamurthy**. STEMSeeds content and photographs belong to their respective creators.

## Scope

This repository contains the website. Organization impact figures shown on the site describe STEMSeeds activities; they are not software usage or performance benchmarks.

