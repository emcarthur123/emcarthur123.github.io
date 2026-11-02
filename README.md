# Everett McArthur — Personal Website

A responsive, static personal website designed for GitHub Pages.

## Publish it

1. On GitHub, create a **public** repository named exactly `emcarthur123.github.io`.
2. Upload the contents of this folder to the repository's root (not the ZIP file itself).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. After GitHub finishes publishing, visit https://emcarthur123.github.io/.

## Before publishing

- Replace `YOUR_EMAIL@example.com` in `index.html` with the public email address you want displayed.
- Add verified links for Google Scholar, ORCID, GitHub, and any other profiles you want to share.
- Review all research descriptions and edit anything that doesn't accurately describe your work.
- Add actual publication titles and links when ready.

## Google indexing

After the site is live:

1. Open Google Search Console: https://search.google.com/search-console/
2. Add the URL-prefix property `https://emcarthur123.github.io/`.
3. Verify ownership using the HTML file or HTML tag method offered by Search Console. If using an HTML file, place it in this repository's root.
4. Submit `https://emcarthur123.github.io/sitemap.xml` in the Sitemaps section.
5. Use URL Inspection to request indexing of the homepage.

Indexing and search placement are not guaranteed or immediate. Keep your name, research description, and public profile links accurate and consistent.

## Files

- `index.html` — page content and SEO metadata
- `styles.css` — layout, typography, colors, responsive styling
- `script.js` — mobile navigation and current year
- `assets/favicon.svg` — browser icon
- `robots.txt` and `sitemap.xml` — crawler guidance
