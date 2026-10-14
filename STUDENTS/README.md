# Students — REALESTATECRM

**Project:** REALESTATECRM  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/prolinkinfo/RealEstateCRM  
**Pinned commit:** `a770042cdab0ff2266f6db2b4bba9984817a3f99`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cfcbc6e8ab2946e412befe4590a6ab5a180c4392baf66918abfce5b6281b876e`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `a770042cdab0ff2266f6db2b4bba9984817a3f99`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `cfcbc6e8ab2946e412befe4590a6ab5a180c4392baf66918abfce5b6281b876e`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
