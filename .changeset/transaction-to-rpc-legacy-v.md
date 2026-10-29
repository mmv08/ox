---
"ox": patch
---

Fixed `Transaction.toRpc` throwing on legacy transactions whose EIP-155 `v` exceeds 255 (chain IDs above 109).
