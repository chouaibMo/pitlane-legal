# Pitlane — Legal documents

Static GitHub Pages site hosting the legal documents for the **Pitlane** F1 prediction app
(privacy policy + terms of service), required by the App Store / Google Play listings, the in-app
GDPR consent screen, and the subscription paywall.

**Live site:** https://chouaibmo.github.io/pitlane-legal/

| Page | URL |
|---|---|
| Privacy Policy | https://chouaibmo.github.io/pitlane-legal/privacy.html |
| Terms of Service | https://chouaibmo.github.io/pitlane-legal/terms.html |

## Before store submission

- [ ] Review both documents (drafted 2026-07-24 by Claude from the app's actual data practices — not legal advice).
- [ ] Set up the `privacy@pitlane.app` mailbox (or replace the address in both pages) — it is currently marked "being set up".
- [ ] Keep the collected-data lists in sync with App Store privacy nutrition labels + Play Data Safety answers (`docs/2026-07-21-ios-privacy-nutrition-labels.md` in the app repo).
- [ ] When the `pitlane.app` domain exists, this site can move there (custom domain on Pages, or re-host) — update the URLs in the app (ideally served via `app_config` so no release is needed).

## Updating

Edit the HTML, commit, push to `main` — Pages redeploys automatically.
