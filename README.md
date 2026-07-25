# eve.aroncreates.com — marketing site

Static HTML/CSS. No build step, no dependencies, no framework.

## Local preview

```bash
python3 -m http.server 8080   # from this directory
```

## Deploy (Vercel, free tier)

```bash
npx vercel --cwd marketing --prod
```

Vercel serves the folder as-is (static detection, no config file needed). Then in the Vercel
project settings add the domain `eve.aroncreates.com`.

## Screenshots

The dashed placeholder boxes are `<div class="screenshot">`. Replace each with:

```html
<div class="screenshot"><img src="img/feed.png" alt="Opportunity feed"></div>
```

Sizing/rounding is already handled by the CSS.

## Org tiles

Placeholder corp names in `index.html` under `#orgs`. Swap for real ones when they exist.
