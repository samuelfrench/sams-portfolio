# Sam's Portfolio TODO

## Active Goal
- [~] Improve the portfolio with modest content updates and stronger styling.
- [~] 2026-08-26: GA4/GSC source instrumentation is ready. `python3 /tmp/verify_batch1.py sams-portfolio --file index.html`, a Python `HTMLParser` closed-head assertion, and `git diff --check` pass. Local Chromium at 1440x1000 and 390x844 rendered the portfolio, exercised the About/mobile-nav interaction, requested the exact `gtag/js?id=G-W350TLWYLT` URL once per viewport, reported zero console/page/request failures and no horizontal overflow, and passed visual review. Remaining: push through `.github/workflows/fly-deploy.yml`, then prove the exact live tags and browser request without exposing the verification token.

## Current Follow-Ups
- [ ] Add real project screenshots or short case-study pages for the strongest projects.
- [ ] Verify live project links periodically; remove or demote anything that is offline.
- [ ] Add the real LinkedIn URL if/when it should be shown publicly.
- [ ] Restore a PDF Merge public URL before adding a live link again; `mergepdfnow.com` did not resolve and the Fly app was suspended on 2026-05-30.

## Completed
- [x] 2026-06-02: Added RV Appliance Code Atlas to featured projects after permanent-domain launch, GA4/GSC automation, and FreshJet closeout verification.
- [x] 2026-05-30: Refreshed hero/about copy, updated major project stats, added TowerStrike, replaced unfinished experience placeholders, tightened styling, and hardened links/mobile nav basics.
