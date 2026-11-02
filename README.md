# QualCode

Free, private, in-browser **qualitative coding and reflexive thematic analysis**:
codebook, quote retrieval, reflexive journal and insights — no NVivo licence required.

**By Joshua Bellot · [Psych & Me](https://substack.com/@psychandme)**

## What it does

- **Select-to-code** — highlight any passage in a transcript and apply a code
  (keyboard: select, then press 1–9). Multi-code highlighting shows where codes overlap.
- **Codebook & themes** — name codes, write definitions, group them into themes,
  re-colour, and see segment counts at a glance.
- **Retrieval** — pull every quote by code, theme or document, ready for write-up.
- **Reflexive journal** — keep the Braun & Clarke-style audit trail of your analytic
  decisions alongside the data.
- **Insights** — code coverage and co-occurrence across documents.
- **Project files** — export/import the whole project as JSON for backup or for sharing
  with a supervision team. Transcripts never leave your device.

## Run it

Single-page app, no build step. Serve the `qualcode/` folder (e.g.
`python3 -m http.server`) and open `index.html`, or just host the folder anywhere static.

## Deploy to GitHub Pages

1. Create a public repo (e.g. `qualcode`) and upload this folder's contents.
2. Settings → Pages → Deploy from branch → `main` / `(root)`.
3. Live at `https://<username>.github.io/qualcode/`.

## Licence & reuse

Free to use, share and adapt for research and teaching. Attribution appreciated.
