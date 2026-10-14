# Educators — OPENLAYERS_PRIOR_DOCS

**Project:** OPENLAYERS_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/openlayers/openlayers  
**Pinned commit:** `69e07d8ad933c3081cc10b8bb4a64023917661aa`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `414b852ddb66cc422d536b9fac9c6727cd45a5c8c9005edf39a3b035d76a2f01`  
**Date:** October 2026

## Teaching with OPENLAYERS_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `414b852ddb66cc422d536b9fac9c6727cd45a5c8c9005edf39a3b035d76a2f01` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
