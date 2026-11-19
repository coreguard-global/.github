<div align="center">

<img src="https://raw.githubusercontent.com/coreguard-global/.github/main/brand/coreguard-lockup-dark.png" width="420" alt="CoreGuard">

# 🗺 CoreGuard Global — Organization Roadmap

**VERIFY • PROTECT • EMPOWER** · *More than security. It's trust.*

Every row carries an honest status label. **VERIFIED ≠ SAFE.** `UNKNOWN` stays HELD.

</div>

---

## ✅ Shipped (evidenced in the [CoreGuard repo](https://github.com/coreguard-global/CoreGuard))

| Network | What | Status |
|---|---|---|
| Core DAO | Commitment anchors on Core Mainnet (chainId 1116) · Evidence Registry with Foundry unit/invariant/fuzz tests | **LIVE / CI-measured** |
| Stellar | Soroban anchor deployed · commit call invoked (ledger 65,337,373) · first signed funded swap confirmed (ledger 65,338,112) · Phase 5 live-verified | **MAINNET EXECUTED** (owner-authorized) |
| Stellar | PSAR/1 pre-sign receipts · AGENT-GATE/1 signed envelope · DEX-GATE/1 example · Agent Commerce Phase 2 (synthetic data) | **BUILT** — wallet integration NOT_BUILT |
| Cross | CGEP/1 receipts · Execution Firewall · ESCROW/1 (DRY_RUN) · badge engine v1.1.0 · bilingual website & brand kit | **SHIPPED** |

## 🟢 Independent external trial — reproduced by a stranger's machine

> **19 Nov 2026 · public record:** [ACP discussion #328](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328)

The **Zambo / AER-1 team** — authors of an independent agent-execution-receipt standard — cloned CoreGuard fresh at commit `5a1f3bd`, counted the CI checks themselves, and ran the VAR/1 pilot kit with one command. The seeded receipt then re-derived **byte-for-byte on three machines** across two Node runtimes.

| Signal | Result | Source |
|---|:--:|---|
| Pilot-kit rows on a fresh clone, run twice | **15 / 15 · exit 0** | [external report](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328#discussioncomment-19722647) |
| CI check runs counted externally on the commit | **12 / 12** | same report |
| Seeded receipt identical on 3 machines (node v24 · v26) | **byte-identical** | [seeded run](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328#discussioncomment-19750155) · [third machine](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328#discussioncomment-19752157) |
| `present-consistent-nonconforming` fixture tests re-run externally | **6 / 6** | third-machine check |
| AER-1 × VAR/1 outcome mapping agreed in public | **5 outcomes mapped** | [mapping note](https://github.com/coreguard-global/CoreGuard/blob/main/docs/aer1-var1-outcome-mapping.md) |

```text
$ node examples/var1-pilot-kit/run.mjs --seed e8cfcd1a93ce50d6d6ace046db9c878ba8e63d3873acc821c9c6d0742cd848cb --at 2026-11-19T14:00:00Z
receipt  urn:sha256:8c6c12bad40471d2c83d8f6ee2a0c07c8649045aa2e96726a4ee31bec13a72c7
body     sha256:386d218c154ae444c878b1b4ee32daf3f5b32f8bd9de363aa854c89f099334b1
```

**What came out of it — shipped Nov 15–19:** `VAR/1` one-command pilot kit · `CG-OUT/1` outcome layer (five outcomes; `ABSENT` / `NOT_CHECKED` never travel as a block) · `CG-ID/1` record identity split · AER-1 parser + full 72-file corpus run · `CG-ANCHOR/1` own anchor service + `CG-COMPOSE/1` composition policy · Agent Commerce discovery, key trust, spend ledger and payment policy · two-column corpus vectors (`present-consistent-nonconforming`, `anchor-unresolvable`).

> **Scope, stated plainly:** this is an independent *technical reproduction* of our open kit by another standards team. It is **not** a commercial pilot, customer, partnership, audit or endorsement. `VERIFIED ≠ SAFE`.

**Founder:** [EslaM HeshAM (MR-X)](https://coreguard-trust-and-defense.lovable.app/founder) · Website: [coreguard-trust-and-defense.lovable.app](https://coreguard-trust-and-defense.lovable.app)

---

## 🔄 In progress

| Item | Target | Status |
|---|---|---|
| SCF #46 RFP-2 — XDR/CAP-Coverage Audit Tool | Deadline 2026-11-20, 9 AM PT | **SUBMISSION-READY** · interest form under review |
| Freighter #3087 technical evaluation | Feedback from maintainers | **COMMENT POSTED** — no endorsement |
| npm SDK publication | After `NPM_TOKEN` | **GATED** |

## 💰 Funding milestones — $150K requested, $0 received

| Milestone | Amount | Deliverable | Status |
|---|---:|---|---|
| M1 | $40,000 | Execution-trust core hardening + reviewer path | Requested |
| M2 | $55,000 | Stellar integration surfaces, SDK, agent/DEX gates | Requested |
| M3 | $55,000 | External pilot + independent review readiness | Requested |
| M4 | — | Mainnet adoption metrics & public report | Planned (post-award) |

## 🧪 14-day pilot timeline (offered, not yet signed)

| Days | Step |
|---|---|
| 1–2 | Scope one real action flow with a partner (wallet / DEX / agent) |
| 3–7 | Put the Execution Firewall + PSAR/1 receipts in front of it (testnet) |
| 8–12 | Measure ALLOW / DENY / HOLD outcomes against acceptance targets |
| 13–14 | Joint report with replayable evidence |

## 🔭 Next

- Pi Network lane — stays **DRY_RUN / PLAN_ONLY** until a real transaction ships.
- Independent third-party security audit — **not done yet**.
- Partnerships, incubators and integrations — [apply here](https://coreguard-trust-and-defense.lovable.app/partnerships).

<div align="center"><sub>🛡 © 2026 coreguard-global · EslaM-X · Core Orange <code>#FF8A00</code> · Deep Core <code>#0B0F14</code></sub></div>
