---
"ox": patch
---

Changed `Transaction.toRpc` to write `v` as `yParity` for typed transactions, as the JSON-RPC spec defines it.
