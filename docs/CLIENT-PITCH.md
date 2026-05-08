# Salon Suite Demo — Pitch Log

## Brief

> Website for Salon Suit Rentals (Fiverr) — Fixed price up to $279, 2-week timeline.
> "I rent salon suits to beauty professionals, aiming to boost tenant sign-ups and deposits. Need sign-up + deposit features. Appealing landing page for beauty professionals. Real estate + beauty niche."

## Demo Built (Spec, Not Quoted)

URL: https://skynetlabs-salon-suite-demo.vercel.app/

3 variants in one page (top-right switcher):
- V1 Editorial — cream / terracotta / brass · Italiana + Inter
- V2 Cinematic — bone / sage / matte black · Cormorant + DM Sans
- V3 Boutique Bold — blush / claret / champagne · Playfair + Manrope

Built sections (every variant):
- Hero w/ ken-burns image, dual CTA (reserve deposit + book tour)
- Trust marquee (24 suites · 92% occupied · 4.9★ · 24/7 · since 2021)
- 3 suite tiers with TRANSPARENT WEEKLY PRICING on the card
- Founder story w/ italic dropcap + license #
- "How tours work" 3-step (reserve → walk through → move in or refund)
- 3 named tenant testimonials w/ IG handles
- 6-Q FAQ accordion with `FAQPage` JSON-LD
- Reservation form: name, email, phone, IG, service category, tier, notes
- Footer w/ NAP + license + Hours

Schema shipped: `HealthAndBeautyBusiness` + per-tier `Offer` + `FAQPage`.

## Why This Beats the Chain Landlords

Every chain audited (Sola, Phenix, MY SALON, Salons by JC, IMAGE, Indie):
- Hides pricing behind a tour gate
- Runs corporate blue/white palette
- Recycles the same 4 differentiators (table stakes)

Two sharp differentiators on this demo:
1. **Pricing on the card** — buyers don't have to call to learn the rent
2. **Refundable online deposit** — locks the suite in 60 seconds, refunds in 3 days if not a fit

## 7 Scope-Unlock Questions Sent

1. **City + neighborhoods served?** Drives all SEO + map schema + which keyword stack we target ("salon suites for rent [Atlanta] / [Buckhead] / [Marietta]" tier).
2. **How many suites + how many tiers + what's the actual weekly rate per tier?** Demo uses placeholder $295 / $395 / $465. We swap your numbers in 10 minutes once you confirm.
3. **Stripe or square or another processor for the deposit?** Determines whether we use a Stripe Payment Link (fastest), Square Online Checkout, or a custom flow.
4. **Do you already have a brand identity (logo / colors / fonts)?** Or shall we lock V1 / V2 / V3 from the demo?
5. **Photos** — do you have 8-12 real interior shots + 1 founder portrait? If not, we ship with curated Unsplash + book a $150 add-on photoshoot (optional).
6. **Lead routing** — where do reservation form fills go? GoHighLevel, GlossGenius, Vagaro, plain email?
7. **Phase 2 hint:** would you want a per-suite "directory listing" page later (one page per tenant, SEO-optimized) so each pro can drive bookings into your building? Often closes a tenant who's still on the fence.

## Pricing Lever Q

8. (Bonus) — **Are you a single-location operator, or planning to scale to 2-3?** Single-location → quoted at the Fiverr cap. Multi-location franchise plan → we layer a `Service` schema + locations index + GBP setup ($350-650 add-on, 2-3× tour-booking lift).

## Pitch Posture

- No fee quoted upfront — let the demo do the work
- "Live on your domain inside the week" if they pick a variant
- Phase 2 upsell teased softly (directory pages, GBP, blog SEO cluster)
- Photo shoot upsell teased ($150 add-on)
