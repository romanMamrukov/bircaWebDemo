# Ghearghe Birca Premium Demo Website

Static production-style demo for a craft distillery. Built with HTML, CSS, and vanilla JavaScript. Suitable for GitHub Pages.

## Structure

```text
index.html
styles.css
script.js
robots.txt
sitemap.xml
assets/
  icons/favicon.svg
  images/placeholders/*.svg
  images/reference/flyer-*.jpeg
```

## Run locally

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload all files from this folder.
3. Go to Settings → Pages.
4. Select Deploy from branch → main → root.
5. Add the custom domain when `birca.lv` access is available.

## Replace placeholder content

Replace files in `assets/images/placeholders/` with real product, equipment, bottle, tasting, and location images. Keep filenames or update paths in `index.html`.

## Legal asset note

The reference flyer images are user-provided. Placeholder SVGs are self-created. Do not add copyrighted product, whisky, vineyard, or distillery photos unless commercial-use rights are confirmed.

## Future roadmap

- Real product photos and professional gallery.
- Booking form connected to email or CRM.
- Latvian/Russian/English language switcher.
- Google Business Profile integration.
- Analytics, conversion tracking, and QR campaign landing page.
- Product CMS/data file for reusable template deployments.
