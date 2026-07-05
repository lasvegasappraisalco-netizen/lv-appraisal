# Las Vegas Appraisal Co. — Website

The site for **Las Vegas Appraisal Co.**, owned and maintained directly by Dan Byrne.

- **Live site:** [lvappraisalco.com](https://lvappraisalco.com)
- **Stack:** Astro 6, deployed to Cloudflare Pages
- **Status:** Live, actively maintained

## Ownership & workflow

Dan Byrne has full owner access to this repository and commits directly to `main`. Cloudflare Pages auto-deploys on every push — no pull requests, no third party involved. The site was originally built by Cody (702 Alliance) but Cody is not currently involved in ongoing changes.

## Key files

- `src/pages/index.astro` — homepage
- `src/pages/about.astro` — team page (Dan, Jim, Sarah)
- `src/pages/litigation-appraisals.astro` — litigation/attorney-facing page
- `src/pages/lenders.astro` — lender-facing page
- `src/pages/contact.astro` — contact + inquiry form
- `src/pages/blog/` — SEO blog posts
- `src/layouts/Base.astro` — shared layout with schema.org JSON-LD, SEO meta, canonical
- `src/styles/global.css` — design tokens

## Commands

\`\`\`
npm install
npm run dev       # localhost:4321
npm run build     # -> ./dist
npm run preview
\`\`\`

## Deploy

Cloudflare Pages auto-deploys on push to `main`.
