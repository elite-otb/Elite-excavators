# Elite-excavators

Static website scaffold for the Elite-excavators site.

## Local preview ⚡

- Install Node.js (optional, `npx` will be used for preview).
- Start a simple static server:

```bash
npm run start
```

This serves files from the `public/` directory on port 8000.

- Build the site (copies `public/` → `dist/`):

```bash
npm run build
```

- Preview the built site:

```bash
npm run preview
```

## Deploy to GitHub Pages 🚀

Push to the `main` branch and GitHub Actions will build and publish the `dist/` artifact to GitHub Pages automatically (workflow: `.github/workflows/pages.yml`).

## Replace with your HTML

Replace `public/index.html` with your HTML file (rename it to `index.html`) and add any assets inside `public/`. If you want, upload your file here and I can add it to the repo.
