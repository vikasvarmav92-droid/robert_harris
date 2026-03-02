# Cafe Rush Mini

A simple, phone-friendly coffee cafe game built as a single `index.html` file.

## Play locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Embed on Carrd

1. Host this folder on any static host (GitHub Pages, Netlify, Cloudflare Pages, etc.).
2. Copy the hosted URL for `index.html`.
3. In Carrd, add an **Embed** element and use:

```html
<iframe
  src="https://your-hosted-site.example/index.html"
  width="100%"
  height="700"
  style="border:0;max-width:480px;"
  loading="lazy"
  allowfullscreen
></iframe>
```

Tip: for mobile-first layouts, set the Carrd container width to 100% and keep max width around 480px.
