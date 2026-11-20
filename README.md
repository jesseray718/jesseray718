<!-- OPENROOT_PUBLIC_ENTRY_V2:START -->
# Jesse Ray McMillen

### Agape synergetic engineering · appropriate technology · local-first systems

I am building OpenRoot: an open technology commons that helps people preserve useful knowledge, inspect its evidence, combine working pieces, and put them to practical use.

The aim is durable capability for people and communities—not more computation for its own sake.

[Explore OpenRoot](https://github.com/jesseray718/openroot) · [Project overview](https://jesseray718.github.io/openroot/) · [Contribute](https://github.com/jesseray718/openroot/blob/f238c5f3c3a0a4ff8ce3498427dacea3207873d6/CONTRIBUTING.md)

## What connects the work

- Knowledge: source identity, SQLite/FTS5 retrieval, corrections, and inspectable records.
- Reusable work: procedures and results with evidence, dependencies, and applicability conditions.
- Appropriate technology: thermal-cascade research, AeroCement, repairable hardware, and community-scale infrastructure.
- Access: useful tools for ordinary phones and used computers, with offline operation as a design priority.

Agape, permaculture, and shared benefit guide the design: preserve what is useful, accept feedback, integrate compatible functions, avoid waste, and support people with the fewest resources.

## Start with a reproducible component

[Read the pathway-cache behavior example](https://github.com/jesseray718/openroot/tree/f238c5f3c3a0a4ff8ce3498427dacea3207873d6/examples/pathway-cache-behavior). From a checkout containing it:

```bash
python3 examples/pathway-cache-behavior/demo.py
python3 examples/pathway-cache-behavior/demo.py --self-test
```

The published example documents four cases and seven tests. It distinguishes ledger integrity from external evidence-file freshness. It uses disposable fixtures, not private databases, and does not execute recorded workflow steps. Run it to inspect the behavior; it is not proof that the whole OpenRoot pipeline is complete.

## Current status and next proof

OpenRoot is an active experimental build. Component examples and local tools exist; automatic all-pod retrieval, correction-aware reuse, and a complete cross-device offline pathway are integration work, not universal guarantees.

The next end-to-end proof is one evidence-backed question, a checked reusable result, offline consumption on another device, and reliable refusal when a required dependency changes.

Physical-system performance requires its own measurements and replication. A hash establishes an artifact identity under its construction; it does not by itself establish scientific truth, measured energy yield, or token value.

## Help build the commons

Start with a narrow contribution: reproduce a test, improve a confusing instruction, report a retrieval miss, document a correction, or contribute a clearly labeled experiment or design packet.

[Contribution guide](https://github.com/jesseray718/openroot/blob/f238c5f3c3a0a4ff8ce3498427dacea3207873d6/CONTRIBUTING.md) · [Issues and discussion of concrete work](https://github.com/jesseray718/openroot/issues) · [Design-packet template](https://github.com/jesseray718/openroot-design-packet-template)

## Licensing and credit

Respect repository licenses and individual file headers. OpenRoot's documented model is GPL-3.0-only for software and CC BY-SA 4.0 for non-code material; see the actual [license](https://github.com/jesseray718/openroot/blob/f238c5f3c3a0a4ff8ce3498427dacea3207873d6/LICENSE) and source headers for applicability. Preserve contributor attribution and third-party terms.

*Engineering as an act of unconditional integration.*
<!-- OPENROOT_PUBLIC_ENTRY_V2:END -->

<details>
<summary>Project foundations and historical notes — earlier status descriptions may be superseded</summary>

The material below is preserved for continuity. Historical performance, deployment, financial, and physical claims are not promoted to current verified results by this update. Follow dated evidence and current source instructions.

# Jesse Ray McMillen · Agape Synergetic Engineering

A1 = DERIVATION · Kernel = AGAPE (R=1.0) · eta = useful_joules / human_joules

Open-source appropriate technology. Offline-first shelter, heat, and compute you can stand up on a phone and a used PC.

Hub: **openroot** · `v1.2.1-popw-ledger` · GPL-3.0
Site: jesseray718.github.io/openroot/

## What is real this week

- **Sealed pathways.** Local 7B coder on the OptiPlex; the phone is the client over SSH/Tailscale. Every inference runs plan - execute - verify - seal into the append-only hash-linked ledger.
- **History scrubbed, gate hardened.** 2,966 commits rewritten clean (zero blobs >100MB, verified), pushed after three rejections taught the lesson: payloads travel by mesh, never by git history.
- **Mesh live.** Two-node Syncthing v2.1.7 mesh (a15 + OptiPlex), direct TLS 1.3 over the tailnet, 54k-file migration verified.
- **Release rail everywhere.** Gate before commit (`bash -n` / `py_compile` / size gate / table drift checks), sealed receipts (GATE_RECEIPT, BUILD_STATUS, append-only WORK_LOG). No rewrites of pushed history.

eta = useful joules / human joules. If a repo does not raise that ratio, it is archived or pinned, not featured.

## Map (do not clone everything)

| Need | Repo | Status |
|---|---|---|
| Engineering hub | `openroot` | live, use this |
| Sealed mesh + thermal | `aperture-mesh` | live stack |
| Dashboard | `canonical` | pins only |
| Sidekick / 12 principles | `wisdom-scaffold` | live kit |
| Material | `aerocement` | spoke |
| Heat | `black-locust-rmh` | spoke |
| η math | `une` / `etaledger` | spoke |
| Thesis | `openroot-thesis` | read, do not fork into a fourth hub |
| Auth UI | `openroot-authui` | extracted per issue #118 |
| Archived merges | `renaissance-protocol`, `OpenCell-Thermal-System`, `civilization2.0` | see openroot |

## Support the work

This is not a product funnel. It is a public workshop. Clone the hub, run the gate, and build the physical layer where you live.

</details>
