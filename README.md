# argument-aloud-ussc5

Brief-document endpoint (part 5 of 9) for the **U.S. Supreme Court** on
[Argument Aloud](https://argumentaloud.org).

- Holds historical brief PDFs (and a handful of scanned covers/notes) under
  `courts/ussc/briefs/<term>/cases/<case>/`, one `files.json` per case and
  one `cases.json` per term, split across 9 sibling repos
  (`argument-aloud-ussc1`…`argument-aloud-ussc9`) so no single repo
  exceeds GitHub's recommended 1GB size.
- Served at `https://ussc5.argumentaloud.org` via GitHub Pages, which adds
  `Access-Control-Allow-Origin: *` so the explorer at `argumentaloud.org`
  can fetch this data cross-origin.

Users never browse this origin directly.
