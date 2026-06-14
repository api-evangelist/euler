# Euler Finance GraphQL API

Euler Finance V2 exposes on-chain vault and account data through GraphQL subgraphs hosted on Goldsky. The subgraphs index factory-created EulerVault and EulerEarn contracts, tracking active accounts (deposits and borrows) and per-account vault balances across all supported EVM-compatible networks.

The API requires no authentication. Queries are submitted as HTTP POST requests with a JSON body containing the `query` field. The Mainnet deployment is the canonical reference; equivalent subgraphs are available for Arbitrum, Base, Sonic, Berachain, Optimism, Avalanche, BSC, and other supported networks by substituting the network name in the path.

**Endpoint:** https://api.goldsky.com/api/public/project_cm4iagnemt1wp01xn4gh1agft/subgraphs/euler-simple-mainnet/latest/gn

**Documentation:** https://docs.euler.finance/developers/data-querying/subgraphs

**References:**
- Documentation: https://docs.euler.finance/developers/data-querying/subgraphs
- GettingStarted: https://docs.euler.finance/developers/data-querying/subgraphs
- GitHubRepository: https://github.com/euler-xyz/euler-subgraph
