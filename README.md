# The Big Day — legal and support pages

Andrew filled identity, address, governing law, and the contact email on 15 November 2026. A lawyer review and the remaining placeholders are still required before publish.

Draft date: **15 November 2026**. These pages are drafts for Andrew and a lawyer. They are not legal advice. They are **not in force**. Do not publish this branch, and do not paste the URLs below into App Store Connect or Google Play, until the placeholders are filled and a lawyer has reviewed the text.

This folder replaces the older Andrew & Melissa one-wedding pages (`index.html`, `privacy.html`, `support.html`) with product-level pages for **The Big Day** (App Store display name: “The Big Day: Wedding Guest App”).

The original checkout at `~/wedding-legal-site` was only a style reference. Do not edit it from this work.

## How these pages are hosted

The site is plain static files. There is no build step, no npm install, and no JavaScript. Shared layout is `styles.css` (system fonts, about 760px wide, light and dark `color-scheme`, no external CSS or font CDN).

GitHub Pages for the repository `andrewreinhard123/wedding-app-legal` already serves this project at the `github.io` URLs below. Today those URLs still show the older Andrew & Melissa pages. Publishing this branch is a later step for Andrew. This work does not deploy.

Serve the approved branch from the **repository root** (`/`). The empty `.nojekyll` file tells GitHub Pages to serve the HTML and CSS as-is, instead of running Jekyll.

A future custom domain (for example a The Big Day marketing site) could serve these same files at paths such as `/privacy`. No custom domain is named here, because none has been chosen.

## Proposed stable URLs

Use these only after review, after the placeholders are filled, and after this branch is what GitHub Pages actually serves.

| Page | URL | Store field |
| --- | --- | --- |
| Home | https://andrewreinhard123.github.io/wedding-app-legal/ | |
| Privacy Policy | https://andrewreinhard123.github.io/wedding-app-legal/privacy.html | App Store and Google Play privacy-policy URL |
| Terms of Service | https://andrewreinhard123.github.io/wedding-app-legal/terms.html | |
| Refund and Cancellation Policy | https://andrewreinhard123.github.io/wedding-app-legal/refunds.html | |
| Support | https://andrewreinhard123.github.io/wedding-app-legal/support.html | Store support / website URL |

## Files

- `index.html` — short landing with links
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `refunds.html` — Refund and Cancellation Policy
- `support.html` — contact, guest FAQs, couple FAQs
- `styles.css` — shared style
- `PLACEHOLDERS.md` — the same checklist, in walk-through form
- `.nojekyll` — static hosting flag

Every page has a visible draft banner.

## Placeholders to fill

The same list is in `PLACEHOLDERS.md`, with a bit more guidance.

On 15 November 2026, identity, governing law, and courts were filled, and Andrew confirmed the 24/7 AI email support policy. The other remaining policy gaps were filled the same day as conservative defaults (labeled “default — Andrew to confirm” in PLACEHOLDERS.md). The designated copyright agent is still an open TODO. The pages are still drafts. A lawyer review is still required before publish.

### Identity and contact

- Done — operator: Andrew Reinhard, a sole proprietor doing business as “The Big Day”. No LLC. Not “Andrew & Melissa Reinhard”.
- Done — business address: 148 Coleto Trail, Bastrop, TX 78602, US.
- Done — contact email: thebigday.support@gmail.com. Andrew confirmed this inbox. The optional second-email placeholder was removed. No second email.

### Law and disputes

- Done — governing law: the law of Texas, together with United States federal law where it applies. The existing conflict-of-law sentence stays.
- Done — courts: courts in Bastrop County, Texas. A consumer may have a right to sue at home that these terms cannot take away.
- Done (default) — no mandatory arbitration clause. Disputes in courts already named; small-claims court allowed where claim qualifies. No class-action waiver. Andrew to confirm.
- Done (default) — minimum age to buy: 18. Applies to the person who pays. Guests who only view or upload are not required to be the buyer. Andrew to confirm.
- Done (default) — liability cap: the greater of fees paid for that wedding in the prior twelve months and US$100. The US$100 floor means a guest is not capped at zero. Limits do not apply where a law forbids them. Andrew to confirm.
- Done (default) — no EU or UK representative. The service is operated from the United States and is not directed at people in the EEA or the UK. Andrew to confirm.
- Done (default) — international transfer safeguard: intended mechanism is the European Commission’s Standard Contractual Clauses and the UK equivalent, to the extent needed and available with our processors. Not claimed to be in place with every processor. Andrew to confirm.

### Setup fees

- Done (default) — round of changes: one consolidated list of edits submitted together. A later list starts a new round. Requests from the couple or an authorized person using the billing or support email. Andrew to confirm.
- Done (default) — $10 change fee: billed on the website via a Stripe invoice or payment link, due before the change is made. Not an in-app purchase. Andrew to confirm.
- Done (default) — setup fee refund rule: stage-based (fully refundable before work starts; 50% after work starts but before publish; non-refundable after publish, except where a law requires otherwise). Statutory rights preserved. Andrew to confirm.
- Done (default) — Signature quote terms: 30-day validity; 50% deposit via Stripe credited toward final price; quote states features included; features not in quote are a new quote. Andrew to confirm.
- Done (default) — prices exclude tax; tax added where required and shown before payment. Andrew to confirm.
- Done (default) — card statement descriptor: THE BIG DAY. Andrew to confirm.

### Storage and retention

Already written and not placeholders: $9.99/month for 10 GB; $2/month per extra 10 GB; cancel anytime; no separate cancellation fee; three full-storage choices with stop new uploads as the default; warnings at 80% and 100%; delete-oldest warns first; at least 30 days’ warning before media deletion when paid storage stops; Download All during that warning; no indefinite retention.

Filled as defaults on 15 November 2026 (Andrew to confirm):

- Done (default) — a wedding can be published without storage, but guests cannot upload until storage is active. Setup does not include media hosting. The “optional” description of storage has been updated across all pages to reflect this rule.
- Done (default) — cancellations take effect at end of current billing period. No partial-month refund. No separate cancellation fee.
- Done (default) — existing subscribers keep their price for at least 12 months after a price increase is announced. At least 30 days’ email notice. After 12 months, new price may apply.
- Done (default) — to remove an extra 10 GB block: go to admin or email support. Takes effect at start of next billing period if usage fits.
- Done (default) — new uploads continue during the 30-day warning unless the wedding is at 100% and set to stop new uploads. Download All available throughout.
- Done (default) — non-media pages (schedule, story, seating, and similar text) stay online in read-only form after the media warning window ends.
- Done (default) — billing records kept 7 years; support emails kept 2 years.

### Notices, copyright, support operations

- Done (default) — material changes announced at least 30 days in advance by email to the billing or account email on file. Andrew to confirm.
- Done — copyright/content reports: Andrew decided on 16 November 2026 not to register a DMCA agent. Pages say: “Email thebigday.support@gmail.com to report content and we’ll remove it.”
- Done — typical reply time and wedding-day support: **confirmed by Andrew, 15 November 2026.** Support is 24/7 by email; handled automatically by an AI support agent, with replies typically within minutes to a few hours; human escalation for refunds and account issues; phone shown only on support.html via the {{SUPPORT_PHONE}} placeholder; no promise of instant or around-the-clock human coverage.

## What a lawyer should review

- The whole draft, before any store listing points at it. It was not written by a lawyer and it is not in force.
- The governing-law and venue sentences, which now state Texas law and courts in Bastrop County, Texas.
- Whether to add arbitration or a class-action waiver. Neither is in the draft.
- The liability cap suggestion (fees paid in the prior twelve months, with a US$50 floor).
- Setup-fee refunds, Signature deposits, and auto-renewal wording. Cancellation timing must match the real Stripe Customer Portal settings and state auto-renewal laws (price, renewal period, how to cancel).
- Whether couples in particular states or countries get a statutory cooling-off right the refund section must honor.
- COPPA framing: the app is not directed to children under 13; photos of children uploaded by adults are treated as the uploader’s content, with a removal path; a parent can email to delete data a child provided.
- Whether a separate “Do Not Sell or Share” link is required. The draft says we do not sell or share for cross-context ads, and it gives the support email for requests.
- International transfers and whether an EU or UK representative is required. No safeguard is claimed.
- Expo is named because the app registers an Expo push token and Expo relays it to Apple or Google. Remove that sentence if push does not ship.
- Film Camera, comments, likes, captions, on-device reminders, and the offline upload queue are described because the current app does those things. Recheck them against the store build.
- Open-Meteo is called from the guest’s device with the venue’s coordinates. The policy says we do not read device GPS, and that Open-Meteo still sees a normal request IP address. Confirm that is the privacy wording you want.
- Prices: Classic $50, Custom **about** $125 (checkout shows the exact amount), Signature $250 and up, storage $9.99 and $2 blocks, changes $10 after 3 rounds. Confirm the live checkout matches before publishing.

## Facts this draft deliberately does not invent

No effective date. No second support email. No phone number committed (support.html uses the {{SUPPORT_PHONE}} placeholder, filled at publish time). No registered LLC. No registered trademark claim. No claim that Standard Contractual Clauses are already signed with every processor. No DMCA designated agent (Andrew decided not to register one).

Filled on 15 November 2026: identity, address, governing law, courts, contact email, and the remaining policy defaults in PLACEHOLDERS.md. Support policy confirmed directly by Andrew on 15 November 2026. Contact email changed to thebigday.support@gmail.com and the DMCA TODO resolved on 16 November 2026.
