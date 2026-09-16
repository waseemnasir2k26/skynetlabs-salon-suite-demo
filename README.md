# Atelier Suites — Salon Suite Rental Demo

Speculative landing page demo for a boutique salon suite rental brief (Fiverr, $279, 2-week scope).

## Status

Last reviewed: September 2026 · release v2026.09

3 design variants in a single HTML file. Sticky top-right switcher, hash-persistent (`#v1` `#v2` `#v3`).

## Variants

| | Axis | Palette | Type | Best for |
|---|---|---|---|---|
| **V1** | Editorial · magazine · warm | Cream / terracotta / brass | Italiana + Inter | High-end hair / color / makeup |
| **V2** | Cinematic · dark · serif | Bone / sage / matte black | Cormorant + DM Sans | Lash / brow / esthetic / clinical-lux |
| **V3** | Boutique bold · type-driven | Blush / claret / champagne | Playfair + Manrope | Mature suite-owner / brand-led |

## Stack

- Static HTML + Tailwind CDN + vanilla JS
- No build step — open `index.html`
- Web3Forms for the reservation form (replace `REPLACE_WITH_WEB3FORMS_KEY`)
- Stripe Payment Link wired into deposit CTA on production (placeholder in demo)
- HealthAndBeautyBusiness + Offer + FAQPage JSON-LD shipped (V1 canonical)

## Why this design beats the chains

Every salon-suite landlord (Sola, Phenix, MY SALON, Salons by JC, IMAGE, Indie) hides pricing behind a tour gate, runs corporate-blue palettes, and ships generic "thrive / dreams / extraordinary" headlines. The buyer is a beauty professional whose own IG is editorial-warm — Aesop / Kinfolk / Hairstory adjacent. This demo flips both:

1. **Transparent rent on the page** — no tour-gated rate sheet
2. **Refundable online deposit** — locks the suite in 60 seconds, refundable in 3 days if not a fit
3. **Editorial-boutique aesthetic** — matches the buyer's mental brand, not a property listing

Built by [SkynetLabs](https://www.skynetjoe.com). MIT license.
