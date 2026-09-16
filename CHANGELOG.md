# Changelog

All notable changes to this project are documented in this file.

## [2026.09] - 2026-09-16

- Maintenance review of skynetlabs-salon-suite-demo — "Atelier Suites", a speculative landing page demo for a boutique salon suite rental brief (Fiverr, $279, 2-week scope), built by SkynetLabs.
- Status: three design variants (editorial / cinematic / boutique bold) in a single static `index.html` with a hash-persistent `#v1`-`#v3` switcher; Tailwind CDN plus vanilla JS, no build step. Ships HealthAndBeautyBusiness + Offer + FAQPage JSON-LD, `robots.txt`, `sitemap.xml` and a `vercel.json` deploy config.
- Reviewed September 2026: documentation refreshed and the repo versioned as v2026.09. No code or design changes.
- Known gaps: the Web3Forms reservation form still carries the `REPLACE_WITH_WEB3FORMS_KEY` placeholder and the Stripe deposit link is a placeholder in the demo; README states MIT but no LICENSE file is present; no CHANGELOG before this release; no tests or CI.
