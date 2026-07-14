---
title: Understanding token features
description: Learn what each TheCoinLab token feature does - mintable, burnable, buy/sell tax, anti-whale limits, presale, and vesting - and when to use them.
---

# Understanding token features

Before you deploy, decide which features your token needs. Each one is a no-code toggle in the configuration step.

## Supply controls

- **Mintable** - create more tokens after launch. Choose this if your tokenomics need a growing supply.
- **Burnable** - permanently remove tokens from circulation to reduce supply.
- **Fixed supply** - the opposite of mintable; the total is locked at deploy time, which many holders trust more.

## Trading controls

- **Buy/sell tax** - take a percentage on trades, routed to a wallet you choose. See [what is a token tax](#) and weigh it carefully - high taxes deter traders.
- **Anti-whale limits** - cap how much any single wallet can hold or trade, to discourage concentration. See [ownership and anti-rug](../security/ownership-and-anti-rug.md).
- **Pausable** - halt transfers when you need to.
- **Blacklist** - block specific addresses.

## Launch mechanics

- **Presale module** - sell tokens before public listing.
- **Vesting** - release tokens on a schedule instead of all at once, common for team or investor allocations.

## Related

- [Add liquidity after deploy](add-liquidity.md)
- [Security and anti-rug](../security/ownership-and-anti-rug.md)
- Back to [Getting started](../getting-started.md)
