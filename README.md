# Legacy LinQ · Website landing page

Live: https://legacylinq.vercel.app

Plain static site: no build step, no dependencies.

- `index.html`: the whole page (HTML, CSS and JS in one file)
- `assets/`: images, site screenshots (`ring/`), scroll videos (`work/`), VSL video, reviews
- `vercel.json`: redirects old `/website/` links to `/`
- `robots.txt`

## Run it locally

```bash
git clone https://github.com/josh12345yauco/LEGACY-WEBSITE-ONLY-LANDING-PAGE.git
cd LEGACY-WEBSITE-ONLY-LANDING-PAGE
python3 -m http.server 4500
```

Then open http://localhost:4500

## Still to do before sending traffic
- Book buttons point to `#book`; the GoHighLevel calendar isn't wired yet
- Two reviews (B&B, Lumen) are placeholder copy marked `data-placeholder`; swap in the real words
