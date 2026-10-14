# Educators — TEXTILE_SIMULATION

**Project:** TEXTILE_SIMULATION  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/rhaberer/4D-Printing-Programmable-Textiles  
**Pinned commit:** `827460cc0408f99507ca49c889abfaab3c2b5cbe`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `82536d8f706323bc8ae6afff8f2cb6adc957b913cf883e2c070bb096dbd54a18`  
**Date:** October 2026

## Teaching with TEXTILE_SIMULATION

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `82536d8f706323bc8ae6afff8f2cb6adc957b913cf883e2c070bb096dbd54a18` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
