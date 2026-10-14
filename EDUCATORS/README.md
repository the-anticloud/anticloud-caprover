# Educators — CAPROVER

**Project:** CAPROVER  
**Category:** INFRA_DEVOPS  
**Upstream:** https://github.com/caprover/caprover.git  
**Pinned commit:** `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f44e02c767a8cf90c6a640aa7fccbb771d16f81e38aeca5a58274aa16805fe6a`  
**Date:** October 2026

## Teaching with CAPROVER

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f44e02c767a8cf90c6a640aa7fccbb771d16f81e38aeca5a58274aa16805fe6a` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
