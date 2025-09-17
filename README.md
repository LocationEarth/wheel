# Alphabet Wheel (mod‑N) — Minimal Release

**Date:** 2025-09-16  
**Version:** v0.1

This package contains the *minimal, reproducible* artifacts for the "Alphabet Wheel (mod‑N)" paper:
- Final **Mod‑N choice** (DE=14, EN=16) with z‑scores against two nulls
- **Stability** summaries (EN: news/web/wiki aligned; DE: Poisson bootstrap)
- **Per‑token** operator diagnostics (load, sector, stability, viability, onset/coda proxies)
- **Top chords** (PMI‑ranked with Δθ)
- **Viability edges** (⊤/~ /⊥ with H‑adapter upgrades)
- Function‑word sanity check tables

## Reproduce (quick)
1. Install Python 3.10+ with `numpy pandas pyyaml`.
2. See `scripts/README_scripts.md` for code snippets (5‑liner) if you want to recompute energy and per‑token tables from the inputs.

## File map
- `data/` — Inputs & derived CSVs used by the figures/tables
- `results/` — Per‑token tables, stability summaries, chords, viability
- `reports/` — Quick check reports & alignment notes
- `LICENSE_CODE` (MIT), `LICENSE_DATA` (CC‑BY‑4.0)

## Citation
See `CITATION.cff`. BibTeX snippet is in `CITATION.bib`.

---

> Note: Bigram counts are derived statistics. Ensure you have rights to redistribute any original text corpora (not included here).
