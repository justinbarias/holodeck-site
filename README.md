# HoloDeck Website

Astro-powered landing page for **HoloDeck**, deployed to GitHub Pages.

## Quickstart

```bash
# scaffolded with: npm create astro@latest holodeck-site
npm install
npm run dev
```

## Build & Deploy

```bash
npm run build
```

The GitHub Actions workflow at `.github/workflows/deploy.yml` builds and deploys to GitHub Pages on pushes to `main`.

## Configuration

Update `astro.config.mjs` with your GitHub username:

```js
export default defineConfig({
  site: "https://<YOUR_USERNAME>.github.io",
  base: "/holodeck-site",
});
```

Repo is ready for Pages; adjust `withastro/action` options in the workflow if your project layout changes.
