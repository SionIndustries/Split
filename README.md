<p align="center">
  <img src="icons/icon-512.png" alt="SPLIT logo" width="120" />
</p>

<h1 align="center">SPLIT</h1>

<p align="center">Instant 50 / 30 / 10 / 10 allocation with committed capital and bill due dates.</p>

---

## What it does

Type an amount and SPLIT instantly divides it into four buckets:

| Bucket    | Share |
|-----------|-------|
| Needs     | 50%   |
| Wants     | 30%   |
| Savings   | 10%   |
| Insurance | 10%   |

Each bucket shows what is **committed** to bills and what is still **available**. A minimalist bill tracker records due dates per bucket, and a currency switcher converts amounts using indicative reference rates.

## Run it

It is a single static page, so there is nothing to install.

- **Locally:** open `index.html` in a browser.
- **On the web:** enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). The app appears at `https://YOUR-USERNAME.github.io/REPO-NAME/`.
- **On a phone:** open the live link, then use "Add to Home Screen" to install it with its icon.

## Your data

Everything is stored in your own browser (`localStorage`). Nothing is sent to a server, and nothing syncs between devices. Clearing your browser's site data erases your entries.

## Tech

- HTML, vanilla JavaScript, Tailwind CSS via CDN, Inter font via Google Fonts
- No build step, no backend, no API keys
- Currency rates are static reference values, not live market rates

## Project layout

```
index.html        the whole app
manifest.json     home-screen install info
icons/            favicon, app icons, maskable icon
```

## Credits

Built with AI assistance.
