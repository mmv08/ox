---
"ox": patch
---

Fixed `TxEnvelopeLegacy.serialize` writing an EIP-155 `v` one too high or too low when `yParity` was 1 and the chain ID was from 4503599627370465 to 4503599627370477, which made the transaction recover to the wrong sender.
