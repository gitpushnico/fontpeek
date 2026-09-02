# FontPeek

Bookmarklet: hover text on any site for computed font, weight, size, line-height, letter-spacing and color; **Copy CSS** in one click. Runs only in your browser. No account, no tracking.

**Live:** [fontpeek.xyz](https://fontpeek.xyz).

Made by [gitpushnico](https://github.com/gitpushnico).

## Quick start

- On the live site, add the bookmark: drag **FontPeek** to the bar (Chrome/Firefox) or **Copy code** → new bookmark URL (Safari).
- Open any page and click the bookmark.
- Hover for readouts; **Copy CSS** for the snippet. Click the panel to lock/unlock; **Esc** closes.

## Privacy

Fonts are files in this repo (`fonts/`), loaded with `@font-face` from the same origin. Nothing is fetched from Google Fonts or any other font CDN at runtime.

The site sets no cookies, loads no analytics, and includes no third-party scripts. The bookmarklet runs only in the current browser tab and does not call FontPeek (or any other host) when you use it on another site.

`vercel.json` enforces this in the Content-Security-Policy: `font-src 'self'` and `connect-src 'none'`.

## How it’s built

**index.html** (landing + bookmarklet), **peek.css** (shared Peek design tokens; copy into [LayoutPeek](https://github.com/gitpushnico/layoutpeek)), and **vercel.json** for static hosting. No build step. Locally: open `index.html` or `npx serve .` from the repo root.

## License

MIT. See `LICENSE`. Font licenses are in `THIRD_PARTY_NOTICES.md`.
