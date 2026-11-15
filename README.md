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

The same list is in `PLACEHOLDERS.md`, with a bit more guidance. Nothing in brackets was invented as fact.

### Identity and contact

- Done — operator: Andrew Reinhard, a sole proprietor doing business as “The Big Day”. No LLC. Not “Andrew & Melissa Reinhard”.
- Done — business address: 148 Coleto Trail, Bastrop, TX 78602, US.
- Done — contact email: andrewreinhard0@gmail.com. Andrew confirmed this inbox. The optional second-email placeholder was removed. No second email.

### Law and disputes

- Done — governing law: the law of Texas, together with United States federal law where it applies. The existing conflict-of-law sentence stays.
- Done — courts: courts in Bastrop County, Texas. A consumer may have a right to sue at home that these terms cannot take away.
- [ARBITRATION — lawyer to decide whether to add a clause] — none is included. No class-action waiver is included.
- [MINIMUM AGE TO BUY — lawyer to confirm] — draft assumes 18 for the paying person.
- [LIABILITY CAP — lawyer to confirm] — suggestion, not a decision: the greater of fees paid for that wedding in the prior twelve months, and US$50.
- [EU OR UK REPRESENTATIVE, IF REQUIRED — Andrew and a lawyer to decide] — none named.
- [INTERNATIONAL TRANSFER SAFEGUARD — lawyer to confirm] — do not claim a transfer tool is in place.

### Setup fees

- [WHAT COUNTS AS ONE ROUND OF CHANGES — Andrew to define] — prices say 3 rounds, then $10. “Round” is undefined.
- [HOW THE $10 CHANGE FEE IS BILLED — Andrew to fill]
- [SETUP FEE REFUND RULES — Andrew and a lawyer to fill] — the draft neither promises nor refuses a setup-fee refund. Cover cancel-before-work, cancel-after-delivery, calling off the real wedding, dissatisfaction, Signature deposits, used change rounds, and mandatory consumer cooling-off rights.
- [SIGNATURE QUOTE TERMS — Andrew to fill] — quote lifetime, deposit, what is included. Price is $250 and up.
- [WHETHER LISTED PRICES INCLUDE TAX — Andrew to confirm]
- [CARD STATEMENT DESCRIPTOR — Andrew to fill]

### Storage and retention

These are already written and are not placeholders: optional storage; $9.99/month for 10 GB; $2/month per extra 10 GB; cancel anytime; no separate cancellation fee; three full-storage choices with **stop new uploads as the default**; warnings at 80% and at 100%; delete-oldest warns first and points people to Download All; at least 30 days’ warning to the billing email before media deletion when paid storage stops; Download All during that warning; no indefinite retention.

Still open:

- [CAN A WEDDING BE PUBLISHED WITH NO STORAGE SUBSCRIPTION — Andrew to confirm]
- [WHEN A CANCELLATION TAKES EFFECT — Andrew to confirm] — end of the paid month, or immediately with no partial-month refund.
- [WHETHER EXISTING SUBSCRIBERS KEEP THEIR PRICE — Andrew to confirm]
- [HOW TO REMOVE AN EXTRA 10 GB BLOCK — Andrew to fill]
- [WHETHER NEW UPLOADS CONTINUE DURING THE 30-DAY WARNING — Andrew to confirm]
- [WHAT HAPPENS TO NON-MEDIA PAGES AFTER STORAGE STOPS — Andrew to confirm] — schedule, story, seating, and similar text.
- [HOW LONG BILLING AND SUPPORT EMAILS ARE KEPT — Andrew and a lawyer to fill]

### Notices, copyright, support operations

- [HOW FAR AHEAD MATERIAL CHANGES ARE ANNOUNCED — Andrew and a lawyer to fill]
- [DESIGNATED COPYRIGHT AGENT, IF YOU REGISTER ONE — Andrew to fill] — optional. Reports go to the support email until an agent exists.
- [TYPICAL REPLY TIME — Andrew to fill]
- [WEDDING-DAY SUPPORT HOURS — Andrew to fill] — or remove if there is no separate coverage.

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
- Whether a DMCA designated agent must be registered before launch.
- Expo is named because the app registers an Expo push token and Expo relays it to Apple or Google. Remove that sentence if push does not ship.
- Film Camera, comments, likes, captions, on-device reminders, and the offline upload queue are described because the current app does those things. Recheck them against the store build.
- Open-Meteo is called from the guest’s device with the venue’s coordinates. The policy says we do not read device GPS, and that Open-Meteo still sees a normal request IP address. Confirm that is the privacy wording you want.
- Prices: Classic $50, Custom **about** $125 (checkout shows the exact amount), Signature $250 and up, storage $9.99 and $2 blocks, changes $10 after 3 rounds. Confirm the live checkout matches before publishing.

## Facts this draft deliberately does not invent

No tax treatment, no card-statement descriptor, no definition of a change round, no setup-fee refund rule, no Signature quote expiry or deposit, no “storage included with setup” period, no partial-month refund rule, no grandfathered subscription price, no retention period for billing email, no effective date, and no second support email. Filled on 15 November 2026: the operator is Andrew Reinhard, a sole proprietor doing business as “The Big Day”; the business address is 148 Coleto Trail, Bastrop, TX 78602, US; the governing law is the law of Texas and disputes are heard in courts in Bastrop County, Texas; the contact email is andrewreinhard0@gmail.com.
