# ACTPI build feedback form

Static, single-page feedback form for ACTPI staff to test the booking portal and
send structured feedback (via Web3Forms) back to Osher Digital.

- Live: https://actpi-build-feedback.osherdigital.com (stable link, reused each week)
  - Renamed 2026-06-05 from `actpi-week1-build-feedback...` to drop the week prefix so
    the link stays the same every round. Needs a DNS CNAME `actpi-build-feedback` →
    `osherai.github.io` at the osherdigital.com DNS, plus the custom domain set in the
    repo's GitHub Pages settings.
- Source of truth for edits lives in the engagement workspace
  (`02-workstreams/booking-module/team-testing-feedback-form.html`); `index.html`
  here is the deployed copy. Update workflow: edit the workspace file, copy it over
  `index.html`, commit, push. GitHub Pages redeploys to the same link automatically.
