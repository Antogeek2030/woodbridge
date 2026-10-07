# Woodsbridge Gutter Specialists — Astro Site

Static Astro site for **woodsbridgegutterspecialsts.com**, optimized for Cloudflare Pages and fast Google indexing.

## Features
- Responsive, mobile-first design
- Navy + amber color theme
- OpenStreetMap embed for 930 Highams Ct, Woodbridge, VA 22191
- SEO: meta tags, canonical, JSON-LD LocalBusiness schema, sitemap, robots.txt
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(703) 555-0199** — search/replace `7035550199` and `555-0199` across the project.

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `woodsbridgegutterspecialsts.com`.
5. Submit `https://woodsbridgegutterspecialsts.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Fully static — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
