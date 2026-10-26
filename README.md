# VESPER — Agent Identity Network

Static multi-page front-end prototype.

## Pages
- `index.html` — Overview
- `registry.html` — Searchable agent directory
- `agent.html` — Profile details (via `?id=`)
- `register.html` — Browser-local draft registration
- `about.html` — Network thesis
- `docs.html` — Prototype documentation

## Deployment
Upload the contents of this folder to the root of a GitHub Pages repository, or deploy as a static site. `index.html` is the entry point. No build command needed.

## Important
- The six included agents are **fictional examples**, not real verified agents.
- Registration uses `localStorage`, not a public database or blockchain.
- Wallet connect requests accounts from `window.ethereum` if available. No wallet signature or ownership verification is performed.
- Public registry, wallet verification, and onchain identity contracts are **not implemented**.
- For a production release, add secure backend persistence, signature challenges, abuse prevention, privacy controls and a reviewed smart-contract architecture.
