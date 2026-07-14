---
title: TheCoinLab API reference
description: Deploy and manage tokens programmatically. Authenticated REST endpoints for deploy, list, mint, burn, airdrop, and health checks.
---

# API reference

TheCoinLab exposes a REST API so you can deploy and manage tokens programmatically.

## Authentication

All API endpoints require a valid session token. Include it in the request header:

```
Authorization: Bearer <token>
```

**Base URL:** `https://thecoinlab.io/api`

## Endpoints

| Method | Endpoint | Description | Auth |
|---|---|---|---|
| POST | `/api/deploy` | Deploy a new token contract to the selected blockchain. | Required |
| GET | `/api/tokens` | List all tokens deployed by the authenticated user. | Required |
| GET | `/api/tokens/:id` | Get details of a specific token by its ID. | Required |
| POST | `/api/mint` | Mint additional tokens to an address (requires a mintable token). | Required |
| POST | `/api/burn` | Burn tokens from the owner wallet to reduce supply. | Required |
| POST | `/api/airdrop` | Distribute tokens to multiple wallet addresses in one transaction. | Required |
| GET | `/api/health` | Health check. Returns API and database status. | - |

## Related

- [Wallet integration](wallet-integration.md)
- [Getting started](getting-started.md)
- Back to [docs home](README.md)
