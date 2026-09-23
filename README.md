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
add a line to `PARTNERS` near the bottom of the file with a short `path` (e.g. `preston`), and
add a matching rewrite to `vercel.json`. Send them `/<path>`; `partners/guide.html?p=<key>` also works.
Loan officer contact details live in the `LO` object in the same script block.
