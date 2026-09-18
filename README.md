# Riggy Websites

Marketing site for Riggy Websites — websites for small businesses, built and deployed by Elijah Riggy (Vancouver, BC).

## Structure

This is a single self-contained static page — no build step, no dependencies.

- `index.html` — the entire site (markup, styles, and script inline)

## Deploying

### Vercel
1. Push this repo to GitHub.
2. In Vercel, click **Add New Project** → **Import Git Repository** → select this repo.
3. Leave the build settings as default (no framework, no build command) — Vercel will serve `index.html` directly.
4. Once deployed, go to **Project Settings → Domains** and add your custom domain.

### Editing
Everything lives in `index.html`. Colors and theme variables are defined as CSS custom properties near the top of the `<style>` block.
