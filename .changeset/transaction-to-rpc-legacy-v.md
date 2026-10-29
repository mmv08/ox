---
"ox": patch
---

Fixed `Transaction.toRpc` throwing on legacy transactions with chain IDs above 109, which also changed a `v` of 0 or 1 to `0x0` or `0x1` instead of `0x00` or `0x01`.
