# Blockscout (blockscout)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
