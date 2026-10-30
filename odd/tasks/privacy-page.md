# Public privacy policy page

## Objective
Publish a standalone, bilingual (es/en) privacy policy page at `privacy.html` so the Chrome Web Store listing has a public policy URL (`https://sereno-phishing.github.io/sereno-landing/privacy.html`).

## Problem and rationale
The landing only has a "Privacidad" section (demo of what is stored), not a policy page. Chrome requires a working public URL in the Developer Dashboard because Sereno transmits the visited URL off the device.

## Authorized scope
sereno-landing only: new `privacy.html` (same visual language, theme and ES/EN switch as `index.html`), links to it from `index.html` (footer and privacy section), README update. Policy text = the existing extension wording (what we send / store / your account / your rights) plus statements already published on the landing (hash+domain only, no page content, Ley N.º 29733 design). No new factual claims.

## Constraints
No invented facts (contact address, third-party sharing, retention period): those gaps are listed below for the owners. No dependencies, no build step (GitHub Pages, plain HTML/CSS/JS). English technical artifacts; es/en strings only in the page dictionary. Language/theme choice shared with `index.html` (same storage keys). No AI attribution in commits.

## Work units
- [x] T1 `privacy.html` + links + README. (written, not yet committed; checked with a Node parity script and HTTP 200)

## Open for the owners (not implemented)
Contact channel for data requests; who is the data controller; whether data is shared with third parties; retention period for history; wording review against the Chrome Web Store User Data policy.

## Next step
Delegated writer implements T1.
