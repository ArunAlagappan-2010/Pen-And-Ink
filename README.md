# Vishkar Interiors — Website Concepts

Six **distinct** website directions for **Vishkar Interiors**, an interior-design studio.
Brief: minimal, black-and-white, inspired by apple.com, **sleek dropdown navigation**, minimal
copy, a **custom logo loading screen**, and **booking a consultation** as the primary action.

**Start here:** open [`index.html`](index.html) — a gallery linking every concept, grouped by
tone, with a shortlist of well-known reference studios.

## The six concepts

| # | Concept | Tone | Signature pattern |
|---|---------|------|-------------------|
| 01 | [Atelier](concept-1-product/index.html) | Pure white | Apple-centered, flyout dropdowns, count-up stats, full booking form |
| 02 | [Editorial](concept-2-editorial/index.html) | Ivory | Split-screen: sticky side-rail with inline expanding dropdowns + serif |
| 03 | [Dark Luxe](concept-3-swiss-grid/index.html) | Charcoal | Gallery-led with a full-width **mega-menu** (thumbnails) |
| 04 | [Gallery](concept-4-cinematic/index.html) | Warm grey | Portfolio-first masonry with a **live category filter** |
| 05 | [Immersive](concept-5-studio/index.html) | Photographic | Fullscreen **auto-rotating room slider**, nav solidifies on scroll |
| 06 | [Type](concept-6-typographic/index.html) | High-contrast B&W | Oversized type, **underline-reveal dropdown panels** |

## Shared across all six (per the brief)

- **Black & white**, Apple-minimal, deliberately sparse copy.
- **Custom logo loading screen** — the Vishkar wordmark animates in, then fades to the page.
- **Sleek dropdown navigation** with all six menus: About Us · Services · Our Portfolio ·
  Office · Careers · Contact Us — each concept implements the dropdown differently.
- **Booking-led** — a persistent "Book a Consultation" CTA and a working booking form
  (name, email, service, preferred date, message) that confirms on submit. Most sections
  funnel toward it.
- Light, restrained motion (scroll reveals only) and full mobile responsiveness.

## Notes

- Each concept is a **self-contained HTML file** — no build step. Just open it.
- Photography is from Unsplash (free to use), in [`assets/`](assets/) (`v-*.jpg`), so pages
  work offline. Replace with Vishkar's real project photography later.
- **Vishkar Interiors** branding and placeholder copy throughout; supply real content later.
- Each concept and the gallery link out to well-known interior studios; full list in
  [`references.md`](references.md).
