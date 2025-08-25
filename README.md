# Single‑Page Website Starter

A production‑ready, **responsive one‑pager** scaffold designed to be cloned for clients. No backend required (Formspree for contact form). Minimal, anxiety‑free CSS utilities for layout and centering.

## What’s included
- Semantic sections (Hero, Services, Work, FAQ, Contact)
- Mobile nav with sticky header
- Layout utilities that solve common pain points:
  - `.stack` (vertical spacing)
  - `.cluster` (row that wraps, controlled gaps)
  - `.grid` (auto‑fit responsive grid)
  - `.switcher` (two‑column on wide screens)
  - `.center`, `.box`, buttons
- Accessible skip link, focus states
- Formspree POST (replace with your endpoint)
- No build step; deploy to Netlify/Vercel/GitHub Pages

## Quick start
1. Open `index.html` in your browser (or use VS Code Live Server).
2. Replace logo and images in `/assets`.
3. Update copy (headlines, pricing, FAQ) in `index.html`.
4. Replace the `action` attribute in the contact form with your **Formspree** endpoint.
5. Deploy:
   - **Netlify**: drag‑and‑drop the folder in the Netlify UI.
   - **Vercel**: `vercel` CLI or connect the repo.

## Acceptance tests (Step 1)
- [ ] The page scales nicely on **360px**, **768px**, and **1280px**.
- [ ] The **Hero** text block is centered/aligned and readable.
- [ ] Cards and gallery **reflow** without breaking layout.
- [ ] The **nav toggle** works on mobile; links scroll to sections.
- [ ] Contact form inputs are focusable and usable.

## Next steps (after Step 1 passes)
1. Add analytics (Plausible or Google Analytics).
2. Add Open Graph image, favicon, and meta tags.
3. Swap content for your **first client niche** (e.g., cafe, trainer).
4. Lighthouse pass ≥ 90 (Performance, SEO, A11y, Best practices).

## License
MIT — free to use and sell as part of your services.
