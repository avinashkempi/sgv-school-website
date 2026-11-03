# SGV School website

A static, responsive website for GitHub Pages.

## Files
- `index.html` — complete site, styling, animations and language switcher
- `assets/sgv-logo.jpg` — supplied SGV School crest
- `assets/sgv-app-preview.webp` — app preview cropped from the supplied SGV app launch artwork

## Deploy with GitHub Pages
1. Create a public repository, for example `sgv-school-website`.
2. Upload `index.html` and the complete `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. After the first deployment, open the Pages URL shown by GitHub.

Do not upload only `index.html`; the `assets` folder is required for the crest and app preview.

## Vercel analytics and performance
The site includes Vercel Web Analytics and Speed Insights scripts. In the Vercel project dashboard, enable **Analytics** and **Speed Insights**, then deploy the site. Vercel will serve the collection scripts for the deployed site; traffic and Core Web Vitals data appear in their respective dashboards after visitors arrive.

## Search visibility
- `robots.txt` allows crawling and points crawlers to `sitemap.xml`.
- The homepage includes canonical and social-sharing metadata plus School structured data using the campus details published on the site.
- Verify the deployed domain with Google Search Console and Bing Webmaster Tools, then submit `https://sgv-school.vercel.app/sitemap.xml`.
- Keep campus and admissions information accurate and current. For a custom domain or separate translated pages, update the canonical, sitemap, and language metadata to match the final URLs.

## Links already configured
- Google Play: https://play.google.com/store/apps/details?id=com.sgvschool.app&hl=en_IN
- School map: https://maps.app.goo.gl/m5F2Ss6jADtgurCZ9

## Before printing QR codes
Open the deployed URL on multiple phones, test all language options and both themes, and scan the final QR code from the printed proof.
