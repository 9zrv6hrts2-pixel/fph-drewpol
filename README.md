# FPH DREWPOL website

Static bilingual website (English + Polish), ready for Cloudflare Pages or another static host.

## Files
- `index.html`, `manufacturing.html`, `products.html`, `faq.html`, `contact.html`: English pages
- `pl/`: Polish equivalents
- `assets/style.css`: responsive styling
- `robots.txt`, `sitemap.xml`: basic SEO files

## Publish with Cloudflare Pages
1. Create a GitHub repository and upload the contents of this folder (not the folder itself).
2. In Cloudflare, open Workers & Pages > Create > Pages > Connect to Git.
3. Select the repository. Framework preset: None. Build command: leave blank. Build output directory: `/` (or `.` if the interface requests a relative directory).
4. Deploy.
5. In the Pages project, add the custom domain `menuiseriejodlowa.com` and follow Cloudflare's DNS instructions.

## Before going live
- Confirm that you control `menuiseriejodlowa.com` and that its DNS can be changed.
- Add real workshop and product photographs; the current visual treatment uses CSS illustrations, not documentary photos.
- Confirm the complete postal address, business email, exact product dimensions, available finishes, order minimums, lead times, packaging, certifications and any custom-production capabilities.
- Confirm whether the 100,000/month maximum capacity is available across the current product mix.
- Review all Polish and English copy with a native speaker familiar with the company's products.
- The contact action currently calls +48 692 745 184; there is no email or quote form because no email address or form destination was supplied.

## Important
The website states only confirmed information supplied for this first draft. It does not claim unverified manufacturing processes, certifications, machinery, or actual monthly output.
