# databank-anchor

Tamper-evident audit logs for data custodians, anchored on Filecoin.

A library and anchoring service that seals a custodian's append-only audit
log into a Merkle tree and anchors only a small commitment on Filecoin, with
inclusion proofs for single statement lines, owner-held checkpoints, and a
standalone verifier. The log itself never leaves the custodian.

## Status

Placeholder. Development has not started yet.

The approach has been validated end to end on the Filecoin Calibration
testnet. The working spike, with its results and the steps to repeat the
check, is at
[databanking-org/filecoin-anchor-spike](https://github.com/databanking-org/filecoin-anchor-spike).

## Related

- [databank](https://github.com/databanking-org/databank), the reference
  implementation of the Databank model
- [databanking.org](https://databanking.org), the Databanking model and its
  research programme

## Licence

Dual-licensed under MIT ([LICENSE-MIT](LICENSE-MIT)) or Apache-2.0
([LICENSE-APACHE](LICENSE-APACHE)), at your option.
