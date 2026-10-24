# Jesse McMillen / OpenRoot

## Receipts, not assertions

I build open-source appropriate technology: practical thermal, shelter,
materials, energy, and local-first computing systems that can be understood,
tested, repaired, and shared. Every claim below traces to a versioned record,
a measurement, or a receipt you can regenerate yourself.

**Latest proof — five-lineage consolidation (2026-10-24).** Four unrelated
history lineages plus main, squash-merged oldest-first into one repository:
five `merge(squash)` commits, 1,006 → 5,470 tracked files, every per-phase
delta reconciled, source branch heads deleted on origin as intended. The
verification tool resolves the whole story from the merge commits themselves —
no trust required, just `bash verify_consolidation_v2.sh . --fetch --remote` —
and it returned `CONSOLIDATION RECEIPT VERIFIED` independently on two machines.

## Start Here

- **[OpenRoot](https://github.com/jesseray718/openroot)** — public ecosystem hub, evidence standards, and repository map
- **[AeroCement](https://github.com/jesseray718/aerocement)** — lightweight construction-material research
- **[Black Locust RMH](https://github.com/jesseray718/black-locust-rmh)** — rocket-mass-heater thermal cascade
- **[OpenCell Thermal System](https://github.com/jesseray718/OpenCell-Thermal-System)** — thermal storage and passive-system research
- **[Design-packet template](https://github.com/jesseray718/openroot-design-packet-template)** — reproducible open-hardware project structure

## Working Principle

```text
evidence → documentation → buildable action → measurement → correction → shared capability
```

I favor low-resource, repairable, offline-capable systems; open documentation;
explicit constraints; and claims that can be checked against measurements. The
guiding ratio is η = J_useful / J_human — a RAPL-backed counter in OpenRoot
banks the joules saved by skipping already-proven pathways instead of
recomputing them.

## Public Status

The account consolidation is complete: OpenRoot is now the single hub where
active hardware, software, templates, and preserved references are mapped in
[docs/REPOSITORIES.md](https://github.com/jesseray718/openroot/blob/main/docs/REPOSITORIES.md).
OpenRoot runs as a local-first knowledge-pod system — sealed workflows, human
gates on every push, receipts for every consequential operation — and is
developed in the open as a working system, not a finished certification.
