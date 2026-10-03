# MindCare Companion — Privacy Policy site

Standalone, static HTML/CSS page that hosts the MindCare Companion Privacy
Policy. No build step, no JavaScript framework, no third-party requests,
no cookies.

## Files

- `index.html` — the page itself
- `assets/styles.css` — styling, using the same sage palette as the MindCare mobile app
- `assets/favicon.svg` — site icon (matches the MindCare app icon)
- `assets/app-logo.png` — copy of the actual MindCare app launcher icon
- `vercel.json` — Vercel config (clean URLs, no trailing slash)

## Local preview

Just open `index.html` in a browser, or:

```bash
npx http-server -p 8080 .
```

Then visit <http://localhost:8080>.

## Before publishing

Open `index.html` and replace the placeholder in the **Contact us** section:

```
<a href="mailto:[support-email-placeholder]">[support-email-placeholder]</a>
```

with your real support email. Also confirm the minimum user age and the
governing law/jurisdiction you would like to state (currently the page assumes
"adults aged 18 and over" and a generic international disclaimer).

## Privacy stance of this page itself

- No external CDN, font, analytics, or pixel.
- No cookies set.
- No JavaScript except the year stamp in `<footer>` (inline, ~3 lines).
- System font stack only.