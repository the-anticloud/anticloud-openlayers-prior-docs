# Students — OPENLAYERS_PRIOR_DOCS

**Project:** OPENLAYERS_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/openlayers/openlayers  
**Pinned commit:** `69e07d8ad933c3081cc10b8bb4a64023917661aa`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `414b852ddb66cc422d536b9fac9c6727cd45a5c8c9005edf39a3b035d76a2f01`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `69e07d8ad933c3081cc10b8bb4a64023917661aa`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `414b852ddb66cc422d536b9fac9c6727cd45a5c8c9005edf39a3b035d76a2f01`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
