# PROOF OF VERIFICATION

## 1. Objective

This document provides a reproducible verification procedure for MoCKA.

## 2. Requirements

- Python 3.12+
- Windows or Linux

## 3. Steps

1. Clone repository
2. Prepare ledger.json
3. Run verification:

\\\ash
python verify_chain.py
\\\

## 4. Expected Output

\\\
CHAIN VERIFIED 44 events
\\\

## 5. Guarantee

If the same result is obtained, the system integrity is verified.

## 6. Notes

- Core runtime is intentionally excluded
- This is a verification-only package
