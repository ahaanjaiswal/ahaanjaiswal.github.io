# Ahaan Site

Personal website for Ahaan, designed for GitHub Pages publishing.

## What was improved

- Semantic HTML (`header`, `nav`, `main`, `footer`) and skip links
- Better accessibility (labels, focus states, ARIA current page, responsive layout)
- Cleaner visual design system (typography, spacing, cards, gradients, timeline)
- SEO essentials (meta descriptions, canonical tags, social metadata, sitemap, robots)
- Deployment extras (`404.html`, favicon)

## Before publishing

1. Replace all `https://example.com` URLs in:
   - `index.html`
   - `journey.html`
   - `robots.txt`
   - `sitemap.xml`
2. Optional: Add an Open Graph image and set `og:image` and `twitter:image` tags.

## GitHub Pages publish steps

1. Push this folder to a GitHub repository.
2. In repo settings: **Pages** → **Build and deployment**.
3. Set source to **Deploy from a branch**.
4. Choose your main branch and root folder (`/`).
5. Save and wait for deployment.

Your site will be available at:
- `https://<github-username>.github.io/<repo-name>/`

If this is a project site (not username.github.io root), keep links relative as they are now.
