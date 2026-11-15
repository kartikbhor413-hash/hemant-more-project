# Mango Stay — Deployment-ready website

This is a static conversion of the original Mango Stay website, preserving the original image bytes.

## Deploy with GitHub + Cloudflare Pages
1. Push the **contents** of this folder to your GitHub repository.
2. In Cloudflare Pages, import the repository, use `main` as production branch, no framework and no build command; publish the repository root (`.`).
3. Test all 13 villas and booking buttons on the generated pages.dev URL before connecting a custom domain.
4. Add the domain through Pages > Custom domains, then follow the DNS instructions.

## Local preview
Run `python -m http.server 8000` in this folder, then open http://localhost:8000. Do not open index.html via file:// for final testing.

## Photo integrity
See PHOTO_SHA256_MANIFEST.json. Each extracted image is an exact copy of the original embedded image data; no resizing, compression or conversion was applied.

## Important
GitHub and Cloudflare deployment require your authenticated accounts. No repository push or live deployment was performed in generating this package.
