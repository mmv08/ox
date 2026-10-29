---
"ox": patch
---

Fixed `TxEnvelopeLegacy.toRpc` writing a pre-EIP-155 `v` for envelopes signed with `TxEnvelopeLegacy.from(envelope, { signature })`.
