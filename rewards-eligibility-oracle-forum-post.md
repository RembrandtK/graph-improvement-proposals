# GIP-0079: Indexer Rewards Eligibility Oracle

We propose a **Rewards Eligibility Oracle** that links eligibility for indexing rewards to provision of service to consumers. Only indexers meeting minimum performance standards receive rewards, to better align incentives with providing value to consumers.

The Graph Protocol currently distributes indexing rewards to indexers without checking whether they serve queries or otherwise maintain quality service.

The proposed Rewards Eligibility Oracle System has two main components: off-chain Oracle Nodes that assess indexer performance against published criteria, and an on-chain Oracle Contract that tracks which indexers are eligible for rewards.

Oracle Nodes evaluate indexers based on service quality metrics and report qualifying indexers to the Oracle Contract. Indexers who meet the standards have their eligibility renewed and are subsequently eligible rewards for a defined period (initially 14 days). Ineligible indexers are denied rewards until they improve their service quality.

For details please refer to: [GIP-0079: Indexer Rewards Eligibility Oracle](https://github.com/RembrandtK/graph-improvement-proposals/blob/rewards-eligibility-oracle/gips/0079.md)
