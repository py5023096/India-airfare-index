# India Airfare Index

A static prototype for a Bharat Airfare Index dashboard. It preserves the supplied dark, data-product visual direction and includes a small route-basket preview.

## Run locally

No build step or dependencies are required. From the repository root, start any static file server:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in a browser. You can also open `index.html` directly, although a local server is recommended for deployment parity.

## Deploy

Deploy the repository as a static site with GitHub Pages, Netlify, Vercel, or any equivalent static host. Set the publish directory to the repository root and use `index.html` as the entry point.

## Data status

This is a front-end prototype. The dashboard uses clearly labeled illustrative mock fares and does **not** scrape airline or OTA sites. The named carriers and aggregators describe intended future collection surfaces only; no live API, scheduled job, or backend index calculation is included.