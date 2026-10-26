# Bittencourt Realty | Website Preview v1.0

Public design prototype for client review, prepared by add2go in October 2026.

**This is a design mockup, not a production real estate website or a working IDX/MLS platform.**

## Live preview (after enabling Pages)

https://add2go.github.io/bittencourt-realty-website/

### One-time GitHub Pages activation

1. Open [Settings > Pages](https://github.com/add2go/bittencourt-realty-website/settings/pages).
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **main** and **/(root)**.
4. Click **Save**. Once the deployment succeeds, open the preview address above.

## What's included

- A responsive visual concept in English and Portuguese.
- Client-provided photographs of the founders and two team members.
- Buying, Selling, Properties, About, Insights and Contact concepts.
- An illustrative search interface only. No IDX data, real listings, prices or availability.
- Contact, WhatsApp and booking examples only. Forms do **not** transmit or store contacts.
- Sample editorial content; Sanity CMS is not connected.
- Placeholder names and professional designations pending verification.

The prototype is completely contained in `index.html`. CSS, JavaScript and optimized images are embedded in the HTML, so no build step is needed. Internal navigation uses hashes, which work under GitHub Pages' repository path.

## Production follow-up

After client design approval, implement Next.js and TypeScript, Sanity CMS, compliant contact routing, actual business contact details, regulatory disclosure, accessibility QA and multilingual SEO. Connect IDX in a separate phase after authorization.

The public repository and Pages preview expose the photographs. A `noindex,nofollow` meta tag discourages indexing but is not a privacy control.

[GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
