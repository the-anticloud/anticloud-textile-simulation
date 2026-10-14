# Ethics — TEXTILE_SIMULATION

**Project:** TEXTILE_SIMULATION  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/rhaberer/4D-Printing-Programmable-Textiles  
**Pinned commit:** `827460cc0408f99507ca49c889abfaab3c2b5cbe`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `82536d8f706323bc8ae6afff8f2cb6adc957b913cf883e2c070bb096dbd54a18`  
**Date:** October 2026

## Position

TEXTILE_SIMULATION is packaged for offline deployment with a verifiable audit trail. The
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
