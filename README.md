# Matchmas 2026 — Contribute edition

Separate edition built from the original Matchmas 2026 source. The original repository is untouched.

## Included
- All 24 original Matchmas days, artwork, animations and timing rules
- One **Contribute** envelope in the shared profile actions, visible on every revealed day
- One responsive accessible submission overlay (story required; name/email optional; permission required)
- No word-count limit advertised

## REQUIRED before enabling live submissions
1. Create a dedicated Gmail address. Availability must be checked in Google's sign-up flow; no address has been reserved.
2. Create a form at https://formspree.io/ and configure the Gmail address as its notification destination.
3. Replace `const MATCHMAS_FORM_ENDPOINT = '';` in `index.html` with the form's verified endpoint URL.
4. Test a real submission and confirm receipt in Gmail, including anonymous submissions.
5. Review your privacy wording and provider's data retention settings before launch.

**Important:** The form is in DEMO MODE until configured. It does not claim to have sent submissions.

## Publish
Create a NEW GitHub repository (for example `matchmas-2026-contribute`) and upload `index.html` plus this README. Enable GitHub Pages from the root of `main`. Do not upload to or modify `matchmas-2026`.

## Local preview
Open `index.html?preview=all` to inspect all 24 days. The live date restrictions remain unchanged.
