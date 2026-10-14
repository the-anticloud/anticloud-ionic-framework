# Ethics — IONIC_FRAMEWORK

**Project:** IONIC_FRAMEWORK  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `754ea433ad4609741586ffbeea96ce6135856ebd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5574783cd2992ae7018d31dd10a63d90762e387c712960060484717796a14e2e`  
**Date:** October 2026

## Position

IONIC_FRAMEWORK is packaged for offline deployment with a verifiable audit trail. The
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
