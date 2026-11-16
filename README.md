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
