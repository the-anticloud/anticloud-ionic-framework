# Students — IONIC_FRAMEWORK

**Project:** IONIC_FRAMEWORK  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `754ea433ad4609741586ffbeea96ce6135856ebd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5574783cd2992ae7018d31dd10a63d90762e387c712960060484717796a14e2e`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `754ea433ad4609741586ffbeea96ce6135856ebd`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5574783cd2992ae7018d31dd10a63d90762e387c712960060484717796a14e2e`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
