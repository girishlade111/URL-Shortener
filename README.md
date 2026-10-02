# URL Shortener

A sleek, cyberpunk-themed **URL shortener** front-end built as a single self-contained
`index.html`. Shorten long links through a third-party shortening API and manage your
shortened URLs in a clean, neon-styled interface with dark/light mode support.

## Features

- **Shorten any URL** — paste a long link and get a compact short URL instantly
- **Cyberpunk UI** — neon-glow aesthetics with Orbitron headings and Share Tech Mono accents
- **Dark / light mode** — theme toggle with smooth animated transitions
- **Custom scrollbar** and responsive layout for all screen sizes
- **Zero build step** — one HTML file, runs anywhere (Tailwind via CDN, Google Fonts)

## Tech stack

- HTML5 + vanilla CSS + JavaScript
- Tailwind CSS (CDN)
- Google Fonts (Orbitron, Share Tech Mono, Inter)

## Quick start

Just open `index.html` in any modern browser — no server, no build step:

```bash
# clone
git clone https://github.com/girishlade111/URL-Shortener.git
cd URL-Shortener

# open index.html in your browser
```

## Project structure

```
URL-Shortener/
├── index.html   # entire app: markup, styles, logic
└── README.md
```

## API note

Shortening is performed via a third-party link-shortening API keyed in the page.
> **Security:** the API key currently lives in the client-side code. If you fork or
> reuse this project, rotate the key and move it behind a server-side proxy so it is
> never exposed in the browser.

## Deploy

Any static host works (GitHub Pages, Netlify, Cloudflare Pages, Vercel) — drop
`index.html` at the site root and it just runs.

---

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)
