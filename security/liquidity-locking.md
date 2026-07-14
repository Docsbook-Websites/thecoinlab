---
title: Liquidity locking guide
description: Lock your token's liquidity so holders trust the pool cannot be pulled. What locking is, why it matters, and how to do it after deploy.
---

# Liquidity locking

Locking liquidity is one of the strongest trust signals you can give holders. It proves you cannot pull the pool.

## What locking means

When you add liquidity you receive LP tokens. Locking them - sending them to a time-locked contract - means the underlying liquidity cannot be withdrawn until the lock expires. That removes the single most common rug-pull vector.

## Why it matters

Holders check whether liquidity is locked before they buy. An unlocked pool signals the owner could remove liquidity at any time; a locked pool signals commitment.

## After you deploy

Add liquidity first (see [add liquidity after deploy](../guides/add-liquidity.md)), then lock the LP tokens for a duration that matches your launch commitment.

## Related

- [Add liquidity](../guides/add-liquidity.md)
- [Ownership and anti-rug](ownership-and-anti-rug.md)
- Back to [docs home](../README.md)
