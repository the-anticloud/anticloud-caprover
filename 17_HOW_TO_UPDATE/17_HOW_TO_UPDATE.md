# How to Update — CAPROVER

**Project:** `CAPROVER`
**Category:** INFRA_DEVOPS
**Domain:** infrastructure and DevOps
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
CAPROVER --version
CAPROVER check-update
```

### Applying Updates
```bash
pip install --upgrade CAPROVER
```

### Rolling Back
```bash
pip install CAPROVER==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
