# cysip — GitHub Pages site

This repository contains the static website for cysip.

Deployment
- GitHub Pages source: main branch / root
- The site entry point is `index.html`.
- Custom domain: `www.cysip.com` (CNAME already added to the repository)

To update the site locally:
1. git clone https://github.com/aishacyprus-dot/cysip.git
2. make changes to `index.html` (or other files)
3. git add/commit/push to `main`

Notes
- If you want the apex domain (cysip.com) to redirect, add the GitHub Pages A records to your DNS provider.
- A `.nojekyll` file is included to prevent Jekyll processing.