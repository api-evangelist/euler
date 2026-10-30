# Euler Finance

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Euler is a permissionless modular lending protocol that enables users to lend, borrow, and build custom lending markets without limits. The platform provides REST APIs for querying vaults, account positions, interest rates, liquidation thresholds, token prices, APYs, reward campaigns, and lending market analytics across multiple EVM-compatible networks.

**Areas:** DeFi · Lending · Borrowing · Finance · Ethereum · Blockchain · Vault · Liquidation · Interest Rates · Permissionless

## Euler Finance on APIs.io

Everything profiled for Euler Finance is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/euler/](https://apis.io/providers/euler/)** — or go straight to one of the APIs or properties below.

### APIs (24)

- [Euler Off-Chain Prices API](https://apis.io/apis/euler/euler-off-chain-prices-api/) — An unofficial REST endpoint for fetching USD-denominated asset prices for ERC-20 tokens across supported networks. Accepts chainId and comma-separated asset…
- [Euler Subgraphs (GraphQL)](https://apis.io/apis/euler/euler-subgraphs-graphql/) — GraphQL-based subgraph endpoints hosted on Goldsky for querying indexed Euler V2 protocol data including vault states, account positions, borrow/supply…
- [Euler V2 TypeScript SDK](https://apis.io/apis/euler/euler-v2-typescript-sdk/) — The recommended TypeScript entry point for applications, bots, scripts, and operational tooling built on Euler V2. Provides protocol data fetching, EVC…
- [Euler Finance Accounts API](https://apis.io/apis/euler/euler-accounts-api/) — Account activity, discovered positions, and sub-account relationships. Legacy nested account payloads are flattened into account-vault rows in v3.
- [Euler Finance APYs API](https://apis.io/apis/euler/euler-apys-api/) — Base and intrinsic APY surfaces. In v3, APY families are split into dedicated endpoints instead of being embedded inconsistently across larger payloads.
- [Euler Finance Auth API](https://apis.io/apis/euler/euler-auth-api/) — Authentication and authorization conventions used across the API, including API keys, admin secrets, and rate-limit behavior.
- [Euler Finance Chains API](https://apis.io/apis/euler/euler-chains-api/) — Chain inventory and per-chain protocol summaries. These replace ad-hoc chain-level aggregates from legacy APIs with explicit, cacheable resources.
- [Euler Finance Curator API](https://apis.io/apis/euler/euler-curator-api/) — Curator-managed metadata such as labels, descriptions, and visibility controls. This is the operator-owned customization surface in v3.
- [Euler Finance Earn API](https://apis.io/apis/euler/euler-earn-api/) — Euler Earn vault resources and historical data. These endpoints are separate from EVK vaults and should be modeled independently in client code.
- [Euler Finance Entities API](https://apis.io/apis/euler/euler-entities-api/) — Platform-admin managed KYBed organization profiles used as backend-owned label and control-plane resources.
- [Euler Finance EVC API](https://apis.io/apis/euler/euler-evc-api/) — Ethereum Vault Connector account event resources. These are separate from account position snapshots and are intended for event-level inspection.
- [Euler Finance FeeFlow API](https://apis.io/apis/euler/euler-feeflow-api/) — Fee-flow event resources and fee-related historical activity.
- [Euler Finance Health API](https://apis.io/apis/euler/euler-health-api/) — Liveness, readiness, and dashboard-friendly platform status checks. Use these for operational monitoring, not for reconstructing full portfolio state.
- [Euler Finance Liquidations API](https://apis.io/apis/euler/euler-liquidations-api/) — Liquidation events and related historical views used for risk analysis and monitoring.
- [Euler Finance Oracles API](https://apis.io/apis/euler/euler-oracles-api/) — Oracle routing, adapter, and price-source inspection endpoints. These expose pricing/oracle internals that were previously harder to inspect externally.
- [Euler Finance Prices API](https://apis.io/apis/euler/euler-prices-api/) — Current and historical token prices. Prices follow v3 source priority rules and return the canonical merged value rather than exposing raw provider-specific…
- [Euler Finance Protocol API](https://apis.io/apis/euler/euler-protocol-api/) — Protocol-wide summary endpoints and aggregate metrics. In v3, these endpoints are explicitly summary-oriented and should be treated as lightweight rollups…
- [Euler Finance PublicAllocator API](https://apis.io/apis/euler/euler-publicallocator-api/) — Public allocator event resources for allocator-level activity and history.
- [Euler Finance Rewards API](https://apis.io/apis/euler/euler-rewards-api/) — Reward campaign APRs and per-account reward breakdowns. Rewards APY is intentionally separate from base vault APY in v3; combine them client-side when you…
- [Euler Finance TermsOfUse API](https://apis.io/apis/euler/euler-termsofuse-api/) — Terms-of-use signature state and audit endpoints.
- [Euler Finance Tokens API](https://apis.io/apis/euler/euler-tokens-api/) — Token metadata, protocol classifications, and related static reference data used throughout the API.
- [Euler Finance Usage API](https://apis.io/apis/euler/euler-usage-api/) — API usage and API key analytics. These endpoints are intended for operators and consumers tracking traffic, rate limits, and key-level activity.
- [Euler Finance Vaults API](https://apis.io/apis/euler/euler-vaults-api/) — Canonical vault resources, vault history, holders, borrowers, and open-interest views. In v3, vault detail is decomposed into focused endpoints instead of…
- [Euler Finance Graph QL API](https://apis.io/apis/euler/euler-graph-ql-api/) — Controlled GraphQL passthrough endpoints for indexer-backed data exploration and compatibility workflows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Euler Finance GraphQL API](https://apis.io/graphqls/euler/euler-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Euler Agentic Access](https://apis.io/agentic-access/euler/euler-agentic-access/)

#### JSON Schema (108)

The data models the API reads and writes.

- [AccountActivity](https://apis.io/schemas/euler/account-activity/)
- [AccountLiquidityValue](https://apis.io/schemas/euler/account-liquidity-value/)
- [AccountPortfolioResponse](https://apis.io/schemas/euler/account-portfolio-response/)
- [AccountPosition](https://apis.io/schemas/euler/account-position/)
- [AccountPositionLiquidity](https://apis.io/schemas/euler/account-position-liquidity/)
- [ApiKeyCreateRequest](https://apis.io/schemas/euler/api-key-create-request/)
- [ApiKeyCreateResponse](https://apis.io/schemas/euler/api-key-create-response/)
- [ApiKeyResponse](https://apis.io/schemas/euler/api-key-response/)
- [ApiKeyUsageResponse](https://apis.io/schemas/euler/api-key-usage-response/)
- [AssetRef](https://apis.io/schemas/euler/asset-ref/)
- [CapHistoryItem](https://apis.io/schemas/euler/cap-history-item/)
- [Chain](https://apis.io/schemas/euler/chain/)
- [ChainStats](https://apis.io/schemas/euler/chain-stats/)
- [CollateralConfig](https://apis.io/schemas/euler/collateral-config/)
- [CollateralConfigWithPrice](https://apis.io/schemas/euler/collateral-config-with-price/)
- [ConfigHistoryItem](https://apis.io/schemas/euler/config-history-item/)
- [CuratorInfo](https://apis.io/schemas/euler/curator-info/)
- [CuratorVaultLabel](https://apis.io/schemas/euler/curator-vault-label/)
- [DataIssue](https://apis.io/schemas/euler/data-issue/)
- [DetailedHealthResponse](https://apis.io/schemas/euler/detailed-health-response/)
- [EarnIncludePrices](https://apis.io/schemas/euler/earn-include-prices/)
- [EarnStrategy](https://apis.io/schemas/euler/earn-strategy/)
- [EarnStrategyAllocationCap](https://apis.io/schemas/euler/earn-strategy-allocation-cap/)
- [EarnVaultBatchItem](https://apis.io/schemas/euler/earn-vault-batch-item/)
- [EarnVaultBatchMeta](https://apis.io/schemas/euler/earn-vault-batch-meta/)
- …and 83 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Euler Context](https://apis.io/jsonld/euler/euler-context/)

#### Examples (91)

Example requests and responses.

- [Completeplatformauthcallback](https://apis.io/examples/euler/completeplatformauthcallback/)
- [Createentity](https://apis.io/examples/euler/createentity/)
- [Createentityaddress](https://apis.io/examples/euler/createentityaddress/)
- [Createentitymember](https://apis.io/examples/euler/createentitymember/)
- [Createplatformadminaccess](https://apis.io/examples/euler/createplatformadminaccess/)
- [Deleteadminapikeysbyid](https://apis.io/examples/euler/deleteadminapikeysbyid/)
- [Deleteentity](https://apis.io/examples/euler/deleteentity/)
- [Deleteentityaddress](https://apis.io/examples/euler/deleteentityaddress/)
- [Getaccountsbyaddressactivity](https://apis.io/examples/euler/getaccountsbyaddressactivity/)
- [Getaccountsbyaddressportfolio](https://apis.io/examples/euler/getaccountsbyaddressportfolio/)
- [Getaccountsbyaddresspositions](https://apis.io/examples/euler/getaccountsbyaddresspositions/)
- [Getaccountsbyaddresssubaccounts](https://apis.io/examples/euler/getaccountsbyaddresssubaccounts/)
- [Getadminapikeys](https://apis.io/examples/euler/getadminapikeys/)
- [Getadminapikeysbyid](https://apis.io/examples/euler/getadminapikeysbyid/)
- [Getadminapikeysbyidusage](https://apis.io/examples/euler/getadminapikeysbyidusage/)
- [Getapysintrinsic](https://apis.io/examples/euler/getapysintrinsic/)
- [Getapysintrinsichistory](https://apis.io/examples/euler/getapysintrinsichistory/)
- [Getapysrewards](https://apis.io/examples/euler/getapysrewards/)
- [Getapysrewardshistory](https://apis.io/examples/euler/getapysrewardshistory/)
- [Getchains](https://apis.io/examples/euler/getchains/)
- [Getchainsbychainidborrowablevaults](https://apis.io/examples/euler/getchainsbychainidborrowablevaults/)
- [Getchainsbychainidstats](https://apis.io/examples/euler/getchainsbychainidstats/)
- [Getcuratorvaults](https://apis.io/examples/euler/getcuratorvaults/)
- [Getdocs](https://apis.io/examples/euler/getdocs/)
- [Getearnvaults](https://apis.io/examples/euler/getearnvaults/)
- …and 66 more published on APIs.io

#### Collections (21)

Postman and Open Collection request collections.

- [Euler Data API (V3) Accounts API](https://apis.io/collections/euler/open-euler-accounts-api/)
- [Euler Data API (V3) Accounts APYs API](https://apis.io/collections/euler/open-euler-apys-api/)
- [Euler Data API (V3) Accounts Auth API](https://apis.io/collections/euler/open-euler-auth-api/)
- [Euler Data API (V3) Accounts Chains API](https://apis.io/collections/euler/open-euler-chains-api/)
- [Euler Data API (V3) Accounts Curator API](https://apis.io/collections/euler/open-euler-curator-api/)
- [Euler Data API (V3) Accounts Earn API](https://apis.io/collections/euler/open-euler-earn-api/)
- [Euler Data API (V3) Accounts Entities API](https://apis.io/collections/euler/open-euler-entities-api/)
- [Euler Data API (V3) Accounts EVC API](https://apis.io/collections/euler/open-euler-evc-api/)
- [Euler Data API (V3) Accounts FeeFlow API](https://apis.io/collections/euler/open-euler-feeflow-api/)
- [Euler Data API (V3) Accounts GraphQL API](https://apis.io/collections/euler/open-euler-graphql-api/)
- [Euler Data API (V3) Accounts Health API](https://apis.io/collections/euler/open-euler-health-api/)
- [Euler Data API (V3) Accounts Liquidations API](https://apis.io/collections/euler/open-euler-liquidations-api/)
- [Euler Data API (V3) Accounts Oracles API](https://apis.io/collections/euler/open-euler-oracles-api/)
- [Euler Data API (V3) Accounts Prices API](https://apis.io/collections/euler/open-euler-prices-api/)
- [Euler Data API (V3) Accounts Protocol API](https://apis.io/collections/euler/open-euler-protocol-api/)
- [Euler Data API (V3) Accounts PublicAllocator API](https://apis.io/collections/euler/open-euler-publicallocator-api/)
- [Euler Data API (V3) Accounts Rewards API](https://apis.io/collections/euler/open-euler-rewards-api/)
- [Euler Data API (V3) Accounts TermsOfUse API](https://apis.io/collections/euler/open-euler-termsofuse-api/)
- [Euler Data API (V3) Accounts Tokens API](https://apis.io/collections/euler/open-euler-tokens-api/)
- [Euler Data API (V3) Accounts Usage API](https://apis.io/collections/euler/open-euler-usage-api/)
- [Euler Data API (V3) Accounts Vaults API](https://apis.io/collections/euler/open-euler-vaults-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Euler Finance — jsonschema rules](https://apis.io/rules/euler/euler-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Euler Authentication](https://apis.io/security/euler/euler-authentication/)
- [Euler Domain Security](https://apis.io/security/euler/euler-domain-security/)
- [Euler Vulnerability Disclosure](https://apis.io/security/euler/euler-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/euler/plans/)

#### Rate limits (1)

Published request limits.

- [Euler V3 Api](https://apis.io/rate-limits/euler/euler-v3-api/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/euler/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.euler.finance/)
- [Documentation](https://docs.euler.finance/)
- [Blog](https://www.euler.finance/blog)
- [Terms of service](https://www.euler.finance/terms-of-service)
- [Privacy policy](https://www.euler.finance/privacy-policy)
- [GitHub](https://github.com/euler-xyz/)
- [Status](https://status.euler.finance)

## API Evangelist rating

**Kin Score 32.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 48.0 |
| Contract governance | 9.8 |
| Operational transparency | 15.8 |
| Developer ergonomics | 28.6 |
| Access clarity | 15.8 |

**Agent readiness 30.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/euler/](https://apis.io/providers/euler/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Euler Finance: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/euler/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
