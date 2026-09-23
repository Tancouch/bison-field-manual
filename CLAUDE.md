# Working notes for Claude

## Brand name
- Use **Bison Mortgage** for the brand in all new and edited material: headings, body copy,
  scripts, emails, signatures, and page titles.
- Keep **Bison Ventures LLC** wherever the licensed entity is named: next to NMLS #2257632,
  in state licensing lines, and in legal disclosures. Do not rewrite those to Bison Mortgage.
- Use the bison mark (the inline SVG in `index.html`, `.mark`) as the logo. Never alter it
  or merge it with partner marks.

## Contact details for Ryan Madrid
- Loan Originator, NMLS #1005605, AZ MLO #923592
- 602 292 8219 · ryanmadrid@gmail.com

## Repo
- `index.html` and `es/` are built output from `build_web.py` in the partner toolkit. Do not
  hand-edit them. Brand changes to the Field Manual belong in the toolkit source.
- `partners/guide.html` is hand-edited. New partner links need no code change: send
  `/for/first-last`. Do not add partner names to `PARTNERS` (names in page source are visible
  to every partner); `/preston` is the one legacy entry.
- Pushes to `main` deploy to Vercel.
