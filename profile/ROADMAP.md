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

## 🟢 External reproduction — a machine that had never touched this kit

> **19 Nov 2026 · public record:** [ACP discussion #328](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328)

An outside payments team — **AgentBadge** (buidl25) — reported an independent run of the VAR/1 pilot kit on a machine that had never touched it: **15/15 rows, exit 0, run twice**, with a byte-identical seeded receipt on a Node runtime outside our tested set. The same public report names one **disagreeing row**: an identical rerun into the same `outDir` reopens a ledger that already recorded the spend, so 3 rows fail on the second run — a real kit limitation, documented rather than hidden. The **AER-1 team** reviewed the model separately in the same thread; that is standards feedback, not a trial, and their name is not attached to the external run.

| Signal | Result | Source |
|---|:--:|---|
| Pilot-kit rows on a fresh clone, run twice | **15 / 15 · exit 0** | [external report](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328#discussioncomment-19722647) |
| Seeded receipt across the reporter's runs | **byte-identical** | [seeded run](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328#discussioncomment-19750155) |
| Same-`outDir` rerun (reported disagreement) | **12 / 15** — stateful spend rows | same report |
| AER-1 team review in the same thread | **standards feedback, not a trial** | [ACP #328](https://github.com/agentic-commerce-protocol/agentic-commerce-protocol/discussions/328) |
| AER-1 × VAR/1 outcome mapping agreed in public | **5 outcomes mapped** | [mapping note](https://github.com/coreguard-global/CoreGuard/blob/main/docs/aer1-var1-outcome-mapping.md) |

**What shipped in that window (our work, not the reporter's):** `VAR/1` one-command pilot kit · `CG-OUT/1` outcome layer (five outcomes; `ABSENT` / `NOT_CHECKED` never travel as a block) · `CG-ID/1` record identity split · AER-1 parser + full 72-file corpus run · `CG-ANCHOR/1` own anchor service + `CG-COMPOSE/1` composition policy · Agent Commerce discovery, key trust, spend ledger and payment policy · two-column corpus vectors (`present-consistent-nonconforming`, `anchor-unresolvable`).

> **Scope, stated plainly:** this is an independent *technical reproduction* of our open kit by an outside payments team (AgentBadge). It is **not** a commercial pilot, customer, partnership, audit or endorsement, and it is **not** an AER-1 trial. `VERIFIED ≠ SAFE`.

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
