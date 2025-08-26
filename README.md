# Project


## Sitemap

A `sitemap.xml` has been generated at the project root: `./sitemap.xml`.

**Base URL:** The sitemap currently uses a placeholder base: `https://www.example.com`.  
Update it to your production domain before submitting to search engines.

### How to update the base URL
1. Open `sitemap.xml` and replace `https://www.example.com` with your site's canonical URL (e.g., `https://fantravel.com`).
2. If your build outputs static files to `build/` or `dist/`, copy `sitemap.xml` into that output directory on deploy.

### How routes were detected
- We scanned for `*.html` files (including `public/`, `build/`, and `dist/` directories).
- `index.html` files are mapped to `/` or their folder path.
- Priorities: `/` = 1.0, shallow paths ≈ 0.7, deeper paths ≈ 0.5.
- Changefreq: root = weekly, others = monthly.

### Submit your sitemap
- Add the full sitemap URL in your `robots.txt`, e.g.:  
  `Sitemap: https://yourdomain.com/sitemap.xml`
- Submit via Google Search Console and Bing Webmaster Tools.
