# Bison Field Manual

Partner education manual for real estate agents and financial advisors working with
Bison Mortgage. Product library, full PITI calculator, and tax-position analyzer.

Static site. Deployed automatically to Vercel on every push to `main`.

Source of truth is `bison-field-manual.html` in the Bison partner toolkit; this repo
holds the built web edition produced by `build_web.py`. Do not hand-edit `index.html`.

Bison Ventures LLC | NMLS #2257632 | Equal Housing Lender

## Partner Playbook

`partners/guide.html` is a standalone partner guide (mortgage cheat sheet, deal scripts,
organization and sales plays). It is hand-edited, not built. To personalize it for a partner,
send `/for/first-last` (e.g. `/for/jane-doe`); the page reads the name from the link and shows
"Prepared for Jane Doe". Nothing needs to change in the repo. `/preston` is an older short link
kept in `PARTNERS` and `vercel.json`.
Loan officer contact details live in the `LO` object in the same script block.
