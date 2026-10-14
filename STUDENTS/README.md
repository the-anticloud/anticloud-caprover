# Students — CAPROVER

**Project:** CAPROVER  
**Category:** INFRA_DEVOPS  
**Upstream:** https://github.com/caprover/caprover.git  
**Pinned commit:** `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f44e02c767a8cf90c6a640aa7fccbb771d16f81e38aeca5a58274aa16805fe6a`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f44e02c767a8cf90c6a640aa7fccbb771d16f81e38aeca5a58274aa16805fe6a`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
