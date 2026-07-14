# Payapays

**Building Stellar-native financial primitives — prediction markets, peer-to-peer stakes, and programmable payouts.**

Payapays is an open-source organisation building trust-minimized financial infrastructure on the [Stellar network](https://stellar.org/). Our products let anyone — anywhere in the world, holding any Stellar asset — put money on the line: predict a real-world outcome, wager against a friend, or run a private tournament, and have it settled deterministically by [Soroban](https://stellar.org/soroban) smart contracts in seconds, for fractions of a cent.

We ship in three layers so the same trust root powers everything we build:

1. **Protocol** — a peer-to-peer stakes primitive as open-source Soroban contracts. The bottom of the stack; the piece users have to trust.
2. **Infrastructure** — oracle aggregation, on-chain indexing, scheduled payouts, notifications, and REST/WebSocket APIs. A facilitator, never a custodian.
3. **Product** — consumer surfaces (prediction markets, private leagues, tournaments, 1:1 wagers) that everyday users actually interact with.

Because prediction markets, private leagues, and P2P wagers all sit on the same protocol, they share one settlement path — Stellar — and inherit the same non-custodial guarantees: every stake is held by a Soroban contract (not by us), outcomes only settle when two independent oracles agree, and there is no operator override, no custodian, no withdrawal button.

- **[PayaStakes](https://github.com/Payapays/Paya-dev)** — flagship prediction market and stakes platform
- Non-custodial by construction — every stake locked in Soroban contracts, never in our database
- Multi-asset (XLM · USDC · EURC · any issued Stellar asset), cross-border, sub-cent fees

MIT-licensed. Contributions welcome.
