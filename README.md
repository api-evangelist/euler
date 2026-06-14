# Euler Finance

Euler is a permissionless modular lending protocol that enables users to lend, borrow, and build custom lending markets without limits. Developers can query vaults, account positions, interest rates, liquidation thresholds, token prices, APYs, and lending market analytics through the Euler V3 REST API, off-chain price endpoints, and GraphQL subgraphs.

## APIs

- **Euler V3 Data API** - Primary REST API for vaults, positions, prices, APYs, rewards, liquidations, and chain analytics. Base URL: `https://v3.euler.finance/v3`. OpenAPI spec: `https://v3.euler.finance/v3/openapi.json`.
- **Euler Off-Chain Prices API** - Unofficial price endpoint for ERC-20 tokens. Base URL: `https://app.euler.finance/api/v1/price`.
- **Euler Subgraphs (GraphQL)** - Goldsky-hosted subgraphs for EulerVaults, EulerEarn, and EulerSwapPools across 15+ networks.
- **Euler V2 TypeScript SDK** - npm package `@eulerxyz/euler-v2-sdk` for protocol data fetching, EVC batch composition, and transaction simulation.

## Resources

- [Documentation](https://docs.euler.finance/)
- [Developer Docs](https://docs.euler.finance/developers)
- [API Reference (Swagger UI)](https://v3.euler.finance/v3/docs)
- [OpenAPI Specification](https://v3.euler.finance/v3/openapi.json)
- [GitHub Organization](https://github.com/euler-xyz/)
- [Subgraph Repository](https://github.com/euler-xyz/euler-subgraph)
- [SDK Repository](https://github.com/euler-xyz/euler-sdks)
- [Bug Bounty ($7.5M)](https://docs.euler.finance/security/bug-bounty)
- [Discord](https://discord.com/invite/CdG97VSYGk)
- [Governance](https://gov.euler.finance)

## Authentication

The V3 Data API supports unauthenticated access (100 req/min per IP) and API key authentication (1000 req/min per key). Contact leonard@euler.xyz to request an API key. Subgraph and off-chain price endpoints are publicly accessible without authentication.
