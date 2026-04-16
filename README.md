# mæd partners — public assets

Public static assets (PDFs, brochures, case studies) for **mæd partners limited**.

Served at **https://assets.maedpartners.com/** via GitHub Pages with a custom subdomain.

## Current assets

| File | Linked from | Notes |
|---|---|---|
| `development-of-strategy-workflow.pdf` | `/sectors/higher-education` Module development tile | Sample module workflow — client name redacted |

## Updating an asset

1. Replace the file in this repo (keep the same filename to preserve existing links)
2. Commit and push to `main`
3. GitHub Pages redeploys within ~1 minute
4. Add `?v=2` (or bump) to any cache-sensitive link on the site

## Adding a new asset

1. Drop the file in the repo root with a URL-safe lowercase-kebab filename
2. Commit and push
3. Reference it from the site as `https://assets.maedpartners.com/<filename>`

## Confidentiality

This is a **public** repository. Anyone can browse it via github.com or fetch any file directly. Do **not** commit:

- Client-identifiable material without explicit permission
- Anything under NDA
- Draft or internal-only documents
- Financial, strategic, or operational material from client engagements

If in doubt, keep it out.
