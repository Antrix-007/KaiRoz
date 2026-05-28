# KaiRoz Landing Site — PRD

## Original Problem
User wanted their KaiRoz landing page (cotton trader satellite intelligence) updated, completed, and packaged so they can easily upload to GitHub and freely host.

## Deliverable
Pure static site — single `index.html` + assets — droppable onto GitHub Pages / Netlify / Vercel with zero build step.

## User Choices
- Structure: single `index.html` file
- Form handling: Google Forms (placeholder URL `GOOGLE_FORM_URL` to swap)
- WhatsApp number: +91 7302223680
- Logo: uploaded by user, saved at `assets/logo.png`
- Favicon: SVG matching brand (green K on black)
- Extras: SEO meta tags, Open Graph, Twitter Card, scroll-triggered reveal animations

## Final File Tree (`/app/site/`)
- `index.html` — full landing page (HTML + CSS + JS inline)
- `assets/logo.png` — brand logo
- `favicon.svg` — tab icon
- `.nojekyll` — GitHub Pages directive
- `README.md` — hosting + customisation instructions

Also packaged as `/app/kairoz-site.zip` for one-click download.

## Sections Implemented
1. Fixed nav with logo + WhatsApp CTA (scroll-aware)
2. Hero with animated tag pill, grid background, dual CTAs
3. Stats bar (15L+, ₹5400Cr, 5 Day, 4-6 Wk)
4. How It Works — 4-step grid with SVG icons
5. Sample WhatsApp signal (Gujarati)
6. Contact form → Google Forms (5 fields)
7. Social links section (WhatsApp / LinkedIn / X / YouTube)
8. Footer with logo, navigation links, copyright

## Tested
- Visual screenshots at hero, mid-fold, signal, form, footer — all render correctly
- Logo + favicon load correctly
- Reveal animations trigger on scroll
- Mobile responsive breakpoints in place

## Backlog / Next Steps
- User to create real Google Form and swap `GOOGLE_FORM_URL`
- User to add real social profile URLs (currently `#`)
- Optional: add OG image (1200x630) instead of using logo for richer link previews
- Optional: connect a custom domain on GitHub Pages

