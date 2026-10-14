# Ethics — OPENLAYERS_PRIOR_DOCS

**Project:** OPENLAYERS_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/openlayers/openlayers  
**Pinned commit:** `69e07d8ad933c3081cc10b8bb4a64023917661aa`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `414b852ddb66cc422d536b9fac9c6727cd45a5c8c9005edf39a3b035d76a2f01`  
**Date:** October 2026

## Position

OPENLAYERS_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
