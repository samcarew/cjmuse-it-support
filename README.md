# CJMuse IT Support

Single-page pitch site for CJMuse IT Support — website builds, email setup, IT support and malware fixes for UK solo tradies, consultants and freelancers.

## Develop

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Output goes to `dist/` — deploy anywhere static (Netlify, Cloudflare Pages, GitHub Pages).

## Configuration

Create a `.env` file with your Formspree form ID:

```
PUBLIC_FORMSPREE_ID=abc123xyz
```

Sign up free at [formspree.io](https://formspree.io) and point the form at your inbox. Without this, the form falls back to a placeholder ID.

## Structure

- `src/pages/index.astro` — page composition
- `src/layouts/Layout.astro` — HTML shell + global styles / design tokens
- `src/components/` — one component per section (Hero, Services, Why, Steps, FAQ, Contact, Footer)
