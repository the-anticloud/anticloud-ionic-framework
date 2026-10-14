# Educators — IONIC_FRAMEWORK

**Project:** IONIC_FRAMEWORK  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `754ea433ad4609741586ffbeea96ce6135856ebd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5574783cd2992ae7018d31dd10a63d90762e387c712960060484717796a14e2e`  
**Date:** October 2026

## Teaching with IONIC_FRAMEWORK

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `5574783cd2992ae7018d31dd10a63d90762e387c712960060484717796a14e2e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
