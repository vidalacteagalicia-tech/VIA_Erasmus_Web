# VIA Project · Accessible Heritage

Static website for the VIA Project — researching accessibility along the Camino de Santiago and the Via Appia.

## Structure

- `index.html` — single-page site (Home, Project, Routes, Research, Inclusion, Resources)
- `styles.css` — styles
- `favicon.svg` — favicon
- `vercel.json` — Vercel config

No build step. To preview locally, open `index.html` or run:

```bash
npx serve .
```

## Deploy on Vercel

1. Go to https://vercel.com/new and import `sr-dtk/via-web`.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Click **Deploy**. Every push to `main` redeploys automatically.
