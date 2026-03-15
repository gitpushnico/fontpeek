# FontPeek — Inspect Typography on Any Website

Hover over any element on any website and instantly reveal its typography — font family, weight, size, line-height, letter-spacing and color. Copy as CSS with one click.

A bookmarklet. No extension, no login, no server.

**Live:** [fontpeek.vercel.app](https://fontpeek.vercel.app)

---

## How it works

Add FontPeek to your browser once (see Setup below). On any website, click FontPeek in your bookmarks bar to activate the inspector. Hover over any text element — the panel follows your cursor and shows all computed font values. Click any element to lock the panel in place, then hit "Copy CSS". Click again to unlock, or press Esc to exit.

Nothing is sent anywhere. There is no backend.

---

## What gets revealed

- **Font Family** — the computed font name
- **Font Weight** — 400, 700, 900…
- **Font Size** — in px as computed by the browser
- **Line Height** — px or unitless value
- **Letter Spacing** — px or em
- **Color** — converted to hex with a color preview dot

---

## Setup

1. Open [fontpeek.vercel.app](https://fontpeek.vercel.app) in your browser
2. **Chrome / Firefox:** drag the **FontPeek** button to your bookmarks bar
   **Safari:** click **Copy code**, create a new bookmark manually, and paste the code as the URL — name it "FontPeek"
3. Navigate to any other website and click the bookmark to activate

Works in Chrome, Firefox, and Safari.

---

## Local Development

```
open index.html
```

Or:

```
npx serve .
```

---

## Project Structure

```
fontpeek/
├── index.html      # Entire app — single file, no dependencies
├── vercel.json     # Deployment config + security headers
├── LICENSE         # MIT
└── README.md       # This file
```

---

## License

MIT — free to use, modify, and deploy.

---

Made by [@gitpushnico](https://github.com/gitpushnico)
