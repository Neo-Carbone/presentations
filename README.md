# Neo Carbone — Presentations

Public, client-facing presentations served via GitHub Pages at:

**[neo-carbone.github.io/presentations](https://neo-carbone.github.io/presentations/)**

## Decks

- **[neogen/](./neogen/)** — NeoGen, malleable software for B2B SaaS. Live demo using real output from running the binary on an HVAC field-service prototype.
- **[fieldnow-m3-launch/](./fieldnow-m3-launch/)** — NeoGen × FieldNOW: M3-α-launch status update (2026-05-12). First AI-generated story shipped end-to-end through the substrate to [`Neo-Carbone/fieldnow-codebase#1`](https://github.com/Neo-Carbone/fieldnow-codebase/pull/1) with three independent layers of verification (local gates · in-PR signed bundle · GitHub Actions). Tagline: *software that bends to user needs — all the while staying compliant.*

## Structure

Each deck lives in its own directory with a self-contained `index.html`. No build step. CDN-hosted libraries (Mermaid, etc.) are loaded inline.

```
index.html              ← landing page
neogen/index.html       ← NeoGen deck
<topic>/index.html      ← future decks
```

## Internal source

Internal versions of these presentations (denser, more technical, internal audience only) live in [Neo-Carbone/presentations-internal](https://github.com/Neo-Carbone/presentations-internal) (private).

## Adding a deck

1. Create a directory at the repo root (`<topic>/`).
2. Drop `index.html` and any assets inside.
3. Update this README and the root `index.html` listing.
4. Push to `main` — Pages auto-deploys.
