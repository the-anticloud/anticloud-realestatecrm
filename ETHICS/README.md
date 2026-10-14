# Ethics — REALESTATECRM

**Project:** REALESTATECRM  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/prolinkinfo/RealEstateCRM  
**Pinned commit:** `a770042cdab0ff2266f6db2b4bba9984817a3f99`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cfcbc6e8ab2946e412befe4590a6ab5a180c4392baf66918abfce5b6281b876e`  
**Date:** October 2026

## Position

REALESTATECRM is packaged for offline deployment with a verifiable audit trail. The
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
