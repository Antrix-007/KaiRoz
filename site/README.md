# KaiRoz — Satellite Intelligence for India's Cotton Traders

A single-page static landing site for **KaiRoz**, delivering weekly satellite-powered price signals to cotton ginners and traders across Saurashtra via WhatsApp.

---

## Live preview

Just open `index.html` in any browser. No build step. No dependencies.

---

## File structure

```
.
├── index.html          # The entire site (HTML + CSS + JS inline)
├── favicon.svg         # Browser tab icon
├── assets/
│   └── logo.png        # KaiRoz brand logo
├── .nojekyll           # Tells GitHub Pages to skip Jekyll processing
└── README.md
```

---

## Free hosting — pick one

### Option 1 · GitHub Pages (recommended)

1. Create a new public repo on GitHub (e.g. `kairoz-site`).
2. Upload **all files** from this folder (keep the structure).
3. Go to **Settings → Pages**.
4. Under **Source**, choose `main` branch and `/ (root)` folder. Save.
5. Your site goes live at: `https://<your-username>.github.io/kairoz-site/`

### Option 2 · Netlify Drop

1. Visit [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this entire folder onto the page.
3. Live in 10 seconds with a free `*.netlify.app` URL.

### Option 3 · Vercel / Cloudflare Pages

Same idea — connect the GitHub repo, no build settings needed (it's pure HTML).

---

## Before you publish — 2 things to update

### 1. Google Form link

The contact form posts to a placeholder Google Form. Replace it with your real one:

1. Create a Google Form with these fields:
   - **Name** (Short answer)
   - **Phone** (Short answer)
   - **Business Type** (Dropdown: Ginner / Trader / Broker / Farmer / Other)
   - **Location / Mandi** (Short answer)
   - **Message** (Paragraph)
2. Click **Send → Link icon** and copy the share URL.
3. In `index.html`, find `GOOGLE_FORM_URL` and replace it with your form URL.

> The form opens in a new tab — simple, free, and the responses land in your Google Sheet automatically.

### 2. (Optional) Update social links

Search for `SOCIAL_PLACEHOLDER` in `index.html` and update the LinkedIn / X / YouTube URLs.

---

## What's inside

- **Hero** with animated tag pill + grid background
- **Stats bar** (market size, satellite cadence, etc.)
- **How It Works** — 4-step process grid
- **Sample WhatsApp signal** in Gujarati
- **Contact form** → Google Forms
- **Social links + Footer**
- **SEO** — Open Graph + Twitter Card meta tags
- **Scroll-triggered reveal animations**
- **Mobile responsive**

---

## Customising

All design tokens live at the top of the `<style>` block in `index.html`:

```css
:root {
  --bg: #070707;       /* page background */
  --green: #c8f135;    /* accent */
  --white: #f2f2f2;
  --card: #0f0f0f;
  --border: #1a1a1a;
}
```

Fonts: Bebas Neue (display), Instrument Serif (italic accent), Instrument Sans (body) — all loaded from Google Fonts.

---

## Contact

WhatsApp: **+91 73022 23680**

© KaiRoz · Satellite Intelligence
