# Pen and Ink

A single landing page for **Pen and Ink** — a studio for *architecture · interiors · urbanism*.
A **full-screen, monochrome architecture slideshow** that loops with smooth cross-fades. No
scroll, a static nav bar, and one evocative word per image. A quiet product showcase.

**Open:** [`index.html`](index.html)

## What it is

- **One page, no scroll.** Everything lives in a single fixed viewport.
- **Full-screen slideshow on loop.** Ten dramatic black-and-white architecture images
  (looking-up towers, facades, geometry) cross-fade every ~5s and loop forever; ← / → to move.
- **Monochromatic.** Each image is grayscaled + contrast-tuned (Pillow) into
  [`assets/mono/`](assets/mono/), in the spirit of the supplied reference shot.
- **Static nav bar** (no dropdowns): the **Pen and Ink** logo top-left, menu (About Us ·
  Services · Our Portfolio · Office · Careers · Contact Us) and an **Enquire** link top-right.
- **One word per image**, bottom-left (Ascent, Rise, Order, …) with a small index and a slim
  bottom progress bar.
- **Loader** with the logo, then the show begins.

## ⚠️ Add the logo file

The nav and loader load **`assets/logo.png`** (your exact "Pen and Ink" lockup). It isn't in the
repo yet, so the page currently shows a script fallback. **Drop your PNG at
`assets/logo.png`** and it will appear automatically — no code change needed.

## Regenerating the images

Source photos go in `assets/mono_src/`; `mono.py` grayscales + contrast-tunes them into
`assets/mono/`. Re-run to add or refresh images, then add `<div class="slide">` entries and a
matching word in the `words` array in `index.html`.

## Open items (your call)

- **Make the GitHub repo private** (repo Settings → change visibility). Note: GitHub Pages won't
  serve a private repo on the free plan — that would disable the live link unless on Pro, or I
  can deploy to Netlify/Vercel instead.
- **Website Gmail.** Enquire links `penandink.studio@gmail.com` — register/confirm it.
