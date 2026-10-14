# Academic Use — CAPROVER

**Project:** CAPROVER  
**Category:** INFRA_DEVOPS  
**Upstream:** https://github.com/caprover/caprover.git  
**Pinned commit:** `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f44e02c767a8cf90c6a640aa7fccbb771d16f81e38aeca5a58274aa16805fe6a`  
**Date:** October 2026

## Scope

CAPROVER is available for academic research under the Apache 2.0 terms of the
Anticommons 0.1.0 dual licence. Citation details are in `23_HOW_TO_CITE`.

## What is available to researchers

- The full upstream source, pinned at `a45cce6b7fc0d30ca431a8d8ce83bef72a5a9913`
- The 16-check assurance register with per-check evidence and hashes
- The AIOSS ledger attesting the project artifacts
- Benchmark output in `BENCH.json`

## Reproducing the result

```
python tools/run_bench.py --out BENCH.json
```

Then recompute any row's SHA3-256 from `ISOLATED_LAB_RESULTS/04_Evidence/`.

## Contact

lois@0-1.gg · 0-1.gg
