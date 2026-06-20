# Stylianos Kitsos Portfolio

A modern personal portfolio built with React, TypeScript, Tailwind CSS, Framer Motion, and Vite.

## Setup

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Project Structure

```text
src/
  components/        Reusable UI helpers
  data/              Central profile and content files
  sections/          Page sections
  utils/             Small utilities
public/images/       Project-owned visual assets
```

## Updating Content

Personal information is stored in `src/data/profile.ts`.

Portfolio lists are stored in `src/data/content.ts`:

- Add projects in `projects`
- Add achievements in `achievements`
- Add experience entries in `experience`
- Add goal items in `goals`
- Add journey dashboard milestones in `dashboardMilestones`

The generated hero image used by the landing page is saved at `public/images/developer-workspace.png`.
