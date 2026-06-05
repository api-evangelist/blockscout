# Blockscout (blockscout)

Blockscout is an open-source EVM blockchain explorer covering 1,000+ L1, L2, and L3 EVM chains. Each Blockscout instance exposes a REST v1 API (legacy), REST v2 API (recommended), GraphQL API, and an Etherscan-compatible API. The hosted Blockscout PRO API at dev.blockscout.com provides multi-chain access with unified routes, plans, and credit-based metering.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/blockscout/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/blockscout/refs/heads/main/apis.yml)

## Tags

- Web3
- Explorer
- Open Source
- EVM
- Multi-Chain
- GraphQL
- REST
- Etherscan-Compatible

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Blockscout REST API v2

Recommended REST API on each Blockscout instance. Endpoints cover blocks, transactions, addresses, tokens, smart-contract verification, and more. Path varies by chain (eth, optimism, base, etc.). Free for self-hosted; subject to PRO API plans on dev.blockscout.com.

- **Human URL:** [https://docs.blockscout.com/devs/apis/rest](https://docs.blockscout.com/devs/apis/rest)
- **Base URL:** `https://eth.blockscout.com/api/v2`

#### Tags

- REST
- EVM
- Explorer

#### Properties

- [Documentation](https://docs.blockscout.com/devs/apis/rest)
- [Postman Collection](collections/blockscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockscout GraphQL API

GraphQL API exposing blocks, transactions, addresses, and tokens.

- **Human URL:** [https://docs.blockscout.com/devs/apis/graphql](https://docs.blockscout.com/devs/apis/graphql)
- **Base URL:** `https://eth.blockscout.com/api/v1/graphql`

#### Tags

- GraphQL
- EVM
- Explorer

#### Properties

- [Documentation](https://docs.blockscout.com/devs/apis/graphql)
- [Postman Collection](collections/blockscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockscout Etherscan-Compatible API

Drop-in Etherscan-style RPC API (action / module query parameters) for easy migration.

- **Human URL:** [https://docs.blockscout.com/devs/apis/rpc](https://docs.blockscout.com/devs/apis/rpc)
- **Base URL:** `https://eth.blockscout.com/api`

#### Tags

- Etherscan-Compatible
- REST
- Migration

#### Properties

- [Documentation](https://docs.blockscout.com/devs/apis/rpc)
- [Postman Collection](collections/blockscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockscout PRO API

Hosted multi-chain Blockscout API with unified routes, plans, and credit-based metering. Replaces the older MyAccount API; old keys do not work on PRO routes.

- **Human URL:** [https://docs.blockscout.com/devs/apis/pro](https://docs.blockscout.com/devs/apis/pro)
- **Base URL:** `https://dev.blockscout.com`

#### Tags

- Pro
- Multi-chain
- Subscription

#### Properties

- [Documentation](https://docs.blockscout.com/devs/apis/pro)
- [Pricing](https://dev.blockscout.com/pricing)
- [Postman Collection](collections/blockscout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockscout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/blockscout)
- [Portal](https://www.blockscout.com/)
- [Documentation](https://docs.blockscout.com/)
- [Developer  Portal](https://dev.blockscout.com/)
- [Git Hub](https://github.com/blockscout)
- [Plans](plans/blockscout-plans-pricing.yml)
- [Rate Limits](rate-limits/blockscout-rate-limits.yml)
- [Fin Ops](finops/blockscout-finops.yml)
- [L L Ms Txt](https://dev.blockscout.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
