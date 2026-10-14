# Students — TEXTILE_SIMULATION

**Project:** TEXTILE_SIMULATION  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/rhaberer/4D-Printing-Programmable-Textiles  
**Pinned commit:** `827460cc0408f99507ca49c889abfaab3c2b5cbe`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `82536d8f706323bc8ae6afff8f2cb6adc957b913cf883e2c070bb096dbd54a18`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `827460cc0408f99507ca49c889abfaab3c2b5cbe`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `82536d8f706323bc8ae6afff8f2cb6adc957b913cf883e2c070bb096dbd54a18`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
