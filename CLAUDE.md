# Oppi Berg Restaurant & Lodge — Demo Site

## What this is
Speculative single-page demo to win the client. Deploys to Render as a static site.
Sent to owners (Sias & Evelene) via WhatsApp + email. Not yet a paid project.

## Build rules (non-negotiable)
- Vanilla HTML/CSS/JS only. No frameworks, no build step. Single page.
- Enquiry form is an ENQUIRY form, not a live booking system. No fake booking backend.
  For the demo, form submits to a simple handler (or mailto fallback) — do NOT fabricate
  availability, payment, or confirmation flows.
- Accurate content only. The venue has NO WiFi, NO air-conditioning, NO mini-bar.
  It is 17km outside Lydenburg on the R37, NOT "in the heart of town."
  Do not reintroduce any amenity not confirmed by the owner.

## Brand
- Name: "Oppi Berg" (two words) as they brand it.
- Palette: warm cream/oat background, warm-brown text/headings, ember/terracotta accent.
- Type: Pinyon Script (logo/accents, large sizes only), Cormorant Garamond (headings),
  Hanken Grotesk (body).
- Tone: warm, unpretentious "lekker plek" — not luxury, not corporate.

## Images
- All photos are the owners' real photos, used swap-ready. Keep each as a single
  clearly-named asset (one path each) so high-res originals can replace them trivially.
- Hero is pre-edited (baked scrim + warm grade). Don't re-process.
- Serve as WebP, sized to display width, hero under ~300KB. Lazy-load below-fold images.

## Accuracy guardrail
If anything in the design bundle conflicts with these rules (especially fabricated
amenities), these rules win. Flag the conflict, don't silently build it.

## Deploy
Static site → Render. Output a single deployable folder.