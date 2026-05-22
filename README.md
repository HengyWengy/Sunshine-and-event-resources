# SunShine Event & Resources Website

This is a static website version of the Base44 page, ready to host on any normal domain.

## Files

- `index.html` - page content and SEO tags
- `styles.css` - responsive design and layout
- `script.js` - mobile navigation behavior
- `server.js` - optional local preview server
- `assets/` - local images copied from the source site

## Preview Locally

Run:

```bash
node server.js
```

Then open `http://127.0.0.1:8766`.

## Publish To A Domain

Upload this whole folder to your web host, Netlify, Vercel, GitHub Pages, Hostinger, cPanel public_html, or any static hosting provider. Set your domain DNS to the hosting provider, then point the provider's publish directory to this folder.

For most hosts, the homepage file must stay named `index.html`.
