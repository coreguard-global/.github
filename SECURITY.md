# Security Policy — CoreGuard Global 🛡

**Reporting a vulnerability** — use GitHub's **private security reporting** on the affected repository ([CoreGuard → Security → Report a vulnerability](https://github.com/coreguard-global/CoreGuard/security)). Do not open a public issue for a security report.

*<sub>للإبلاغ عن ثغرة: استخدم التبليغ الخاص عبر «Security → Report a vulnerability» في المستودع المتأثر — لا تفتح مشكلة عامة إطلاقًا.</sub>*

## What we promise

- **Acknowledgement** within 72 hours.
- A **deterministic, replayable evidence path** for any fix — every patch lands CI-green with its state snapshot pinned (`docs/status.md` is the one source of truth).
- External bounty scope is defined contract-by-contract inside the affected repo; **core anchors on Core Mainnet (chainId 1116) carry the highest severity tier.**

## Honest scope

- `UNKNOWN` stays **HELD** — we never rate a report as fixed without a replayable artifact.
- Bitcoin-DeFi surfaces live **per-ecosystem**: Core DAO (mainnet, live) · Stellar (`DRY_RUN/PLAN_ONLY`) · Pi Network (`DRY_RUN/PLAN_ONLY`) — reports against `DRY_RUN` surfaces are triaged as design feedback, not live exploits.

— © 2026 coreguard-global · EslaM-X
