# DNA-X Marketing: website code (dnaxmarketing.com)

DNA-X is a PsikiQ Solutions company. This repo holds the **generated** website code only. It's built from a private build, so don't edit these files by hand: changes are made in the build and re-published here.

**Temporary preview (until the domain is live):** https://nexus-mkii.github.io/dnax-marketing/
The preview is hidden from search engines (noindex). The yellow "Preview mode" banner at the top is expected; it disappears once the GHL checkout links are wired in.

---

## For Rob: installing on GHL

**Where:** GHL → PsikiQ sub-account → **Sites → Websites → DNA X folder → DNA-X Marketing → Home → Edit**.
The website and the blank Home page already exist.

Pick **one** of these two methods.

### Option A: one element (fastest)
1. Add one **full-width section**, then one **Custom Code** element inside it.
2. Paste the whole of [`ghl/dnax-home-ghl.html`](ghl/dnax-home-ghl.html) and save.

### Option B: sectioned (edit each part on its own later)
Add **one full-width section per file**, each with **one Custom Code element**. Paste the files **in this order**:

| # | File | What it is |
|---|---|---|
| 1 | [`sections/01_foundation.html`](sections/01_foundation.html) | Styles, fonts and scripts. **Must be first**, because everything else depends on it |
| 2 | [`sections/02_hero.html`](sections/02_hero.html) | Hero |
| 3 | [`sections/03_system.html`](sections/03_system.html) | The system + the Six A's |
| 4 | [`sections/04_tier1-carousel.html`](sections/04_tier1-carousel.html) | Tier 1: Content Pack Pro, Email Rescue, Partner Growth, WOW Bundle |
| 5 | [`sections/05_dnax-carousel.html`](sections/05_dnax-carousel.html) | DNAx builds: Quiz Endpoint, GEO + SEO, BizCard |
| 6 | [`sections/06_bundles-carousel.html`](sections/06_bundles-carousel.html) | Bundles |
| 7 | [`sections/07_funnel.html`](sections/07_funnel.html) | How the funnel works |
| 8 | [`sections/08_faq.html`](sections/08_faq.html) | FAQ |
| 9 | [`sections/09_close-footer.html`](sections/09_close-footer.html) | Closing calls to action + footer |

**Tip:** open a file on GitHub, click **Raw**, then select all and copy.

### For both options
- In each section's settings, set **padding to 0** and **width to full**.
- **Save** and **Preview**. **Don't publish** until Chris confirms the domain and the checkout links.

### Not wired yet (Chris will supply)
- **Checkout links:** they live in one place, `DNAX.offerMap` near the bottom of `01_foundation.html` (or the top of the single-element file). Replace each `#REPLACE_GHL_PRODUCT_URL_*` with the GHL product or order-form link. Replace `#REPLACE_GHL_BOOKING_URL` with the booking calendar link. The yellow banner disappears once they're all real.
- **The hero button** points at `#dnax-diagnostic`, a placeholder until the marketing diagnostic exists.
- **The domain:** dnaxmarketing.com is connected in GHL once it's bought.
