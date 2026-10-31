# DNA-X site: change brief, 15 October 2026

For Rob (or Chris) to apply in GHL. Each change gives the section file, the exact text to find, and the replacement.
Paste the changed sections the usual way (see `README.md`).

## Prices: Build E goes to $2,997

Build E moves from **$2,597 to $2,997**. Every bundle that includes Build E moves by the same $400 and keeps its
current saving.

| Product | Strike-through (was → now) | Price (was → now) | Saving |
|---|---|---|---|
| Build E — GEO + SEO Foundation | – | $2,597 → **$2,997** | – |
| Pipeline Engine (D + E) | $6,094 → **$6,494** | $5,597 → **$5,997** | $497 |
| Authority Stack (E + F) | $4,594 → **$4,994** | $4,097 → **$4,497** | $497 |
| Complete Factory (D + E + F) | $8,091 → **$8,491** | $7,597 → **$7,997** | $494 |

Each price appears in three places per product: the card price, the strike-through line (bundles) and the button text
("Start Build E — $2,597"). They are in:

- `sections/05_dnax-carousel.html` (Build E card) and `sections/06_bundles-carousel.html` (bundles)
- `index.html` (the full page)
- `ghl/dnax-home-ghl.html` (the GHL page copy)

**Also update the checkout products** behind the buttons (`data-offer="build-e"`, `bundle-pipeline`,
`bundle-authority`, `bundle-complete-factory`), so the amount charged matches the page.

## 1. Citations: replace Apify with the citation distributor

We submit citations through a citation distributor (BrightLocal or similar), not Apify. Its costs are built into the
price, and it reaches a large number of directories quickly.

### 1a. Build E card, "See what's inside"

**File:** `sections/05_dnax-carousel.html` (the same text also appears in `index.html` and `ghl/dnax-home-ghl.html`)

Find:

> **24-citation foundation pack** — submitted via Apify automation, then manually verified. Designed to give your SEO
> partner a clean base — not to compete with their work.

Replace with:

> **24-citation foundation pack** — submitted through our chosen citation distributor (BrightLocal or similar), which
> reaches the major directories quickly, then manually verified. Distributor costs are included. Designed to give your
> SEO partner a clean base — not to compete with their work.

### 1b. FAQ

**File:** `sections/08_faq.html` (also in `index.html` and `ghl/dnax-home-ghl.html`)

Find the question:

> Apify automation vs VA Manual Citations — what's the difference?

Replace with:

> Distributor citations vs VA Manual Citations — what's the difference?

Find the answer:

> Base Build E delivers 12 foundation citations submitted via Apify automation, then manually verified. Build E also
> includes 12 VA hand-placed citations on niche, high-trust sites — guild directories, chambers, trade associations,
> industry review sites. Total: 24 citations. Both are foundation work — not full SEO maintenance.

Replace with:

> Base Build E delivers 12 foundation citations submitted through our chosen citation distributor (BrightLocal or
> similar), then manually verified; the distributor's costs are included. Build E also includes 12 VA hand-placed
> citations on niche, high-trust sites — guild directories, chambers, trade associations, industry review sites. Total:
> 24 citations. Both are foundation work — not full SEO maintenance.

## 2. Email Database Rescue: one product, three starting points (optional)

The same 8-week protocol works whatever state the list is in. The card should say so, so cold-start buyers recognise
themselves.

**File:** `sections/04_tier1-carousel.html` (also in `index.html` and `ghl/dnax-home-ghl.html`)

Find the subtitle:

> Cold list re-ignited. 8-week protocol. Instant. $497.

Replace with:

> Ramp, Rescue or Reset. One 8-week protocol. Instant. $497.

Add as the first bullet, above "Staged 8-week re-engagement sequence":

> **Ramp** (no list yet: build it warm from day one) · **Rescue** (cold list re-ignited) · **Reset** (lapsed list
> re-baselined)

Keep the product name, the price and the button as they are.

## Check after pasting

- Search the live page for "Apify" and "2,597": neither should appear.
- Build E shows $2,997; the three bundles show $5,997, $4,497 and $7,997, with the new strike-through prices.
- Test one checkout button: the amount charged matches the page.
- Preview on mobile.
