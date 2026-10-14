# Ethics — CAPROVER

**Project:** CAPROVER  
**Category:** INFRA_DEVOPS  
**Upstream:** https://github.com/caprover/caprover.git  
**Pinned commit:** `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f44e02c767a8cf90c6a640aa7fccbb771d16f81e38aeca5a58274aa16805fe6a`  
**Date:** October 2026

## Position

CAPROVER is packaged for offline deployment with a verifiable audit trail. The
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
