# PasarSegar — Devpost write-up

## Elevator pitch

From farm to your door in 24 hours. PasarSegar is a farm-to-table marketplace
where city buyers order fresh produce directly from local farmers — with the
farmer's name, village, and harvest date on every product.

## Inspiration

City grocery apps sell you a tomato. They never tell you who grew it, when it
was picked, or whether the farmer got a fair price. Meanwhile small farmers
struggle to reach buyers without middlemen taking most of the margin.
PasarSegar closes that gap with a marketplace that treats the farmer as the
hero of the product page, not a footnote.

## What it does

Browse 14 fresh products with farmer name, village, harvest date, price,
freshness badge, organic tag, and rating. Filter by category, search live,
sort by freshness, price, or rating. Open any product for the farmer's story,
harvest freshness, and nutrition notes. Add to cart, watch the free-delivery
progress bar, then check out in 3 steps — delivery address, payment method
(transfer, cash on delivery, QRIS), confirm — and get an order number plus a
4-stage delivery timeline from Ordered to Arriving. Meet the growers in the
farmer stories section.

## How we built it

Single-file HTML + CSS + vanilla JavaScript. Zero install, no build step, no
backend, no external assets — every visual is inline SVG + CSS. Mobile-first
with an editorial design system: warm cream background, deep leaf green,
tomato accent, serif display type. Accessible throughout: skip link, real form
labels, focus-visible outlines, aria-live cart updates.

## Challenges we ran into

Making a marketplace feel warm instead of transactional. The fix was editorial:
every product card leads with the farmer and the harvest date, not the price —
so the design sells trust first, then produce.

## Accomplishments that we're proud of

A complete shopping journey — browse to order confirmation with a delivery
timeline — in one self-contained file that works offline, with a design system
that feels like a real brand rather than a wireframe.

## What we learned

Good marketplace UX is about trust: who grew it, when it was picked, and what
happens after you pay. Get those three answers right and the rest of the flow
feels effortless.

## What's next for PasarSegar

Real farmer onboarding, harvest subscriptions (weekly vegetable boxes), and
delivery tracking with live courier location.

## Built with

HTML, CSS, JavaScript
