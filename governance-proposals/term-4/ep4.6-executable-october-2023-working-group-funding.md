| description                                                                                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| This proposal executes all three Working Group funding requests for the October 2023 funding window as passed in EP 4.4.1, EP 4.4.2, and EP 4.4.3. For more detail, view the ENS Governance docs at https://basics.ensdao.org 1 |

# [EP 4.6] [Executable] October 2023 Working Group Funding

  
  | **Status**            | Pending                                                                                                                                      |
  | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
  | **Discussion Thread** |  [Discourse](https://discuss.ens.domains/t/ep-4-6-executable-october-2023-working-group-funding/18064)                                                                                              |
  | **Discussion Temp Check** |  N/A                                                                                              |
  | **Votes**             | [Agora](https://agora.ensdao.org/proposals/815480450036429026998617227498389389237567897899533433380564585906006968770)                                                                                                                                     |
  

# Abstract 
 ### [EP 4.4.1 — ENS Ecosystem Working Group](https://discuss.ens.domains/t/4-4-1-social-funding-request-ens-ecosystem-working-group/17995)

The ENS Ecosystem Working Group requests funding of **409,000 USDC** from the ENS DAO treasury.

The ENS Ecosystem Working Group is responsible for growing and improving the ENS Ecosystem by funding people and projects that are ENS-specific or ENS-centric. In line with Article III of the ENS DAO Constitution, the requested funds will be used to support projects and builders contributing to the development and improvement of the ENS protocol and the ENS ecosystem.

### [EP 4.4.2 — MetaGovernance Working Group](https://discuss.ens.domains/t/4-4-2-social-funding-request-ens-meta-goverance-working-group/17994)

The Meta-Governance Working Group requests funding of **376,000 USDC, 40 ETH, and 52,300 $ENS** from the ENS DAO treasury.

This MetaGovernance Working Group will use this funding to support the governance processes of the ENS DAO as well as manage and build infrastructure to support the ENS DAO and Working Groups.

### [EP 4.4.3 — Public Goods Working Group](https://discuss.ens.domains/t/4-4-3-social-funding-request-ens-public-goods-working-group/17996?u=5pence.eth)

The ENS Public Goods Working Group requests funding of **218,204 USDC, and 35 ETH** from the ENS DAO treasury.

The Public Goods Working Group will be use this funding to support projects and builders as provisioned by Article III of the ENS DAO Constitution, which provides for the funding of public goods in web3.

# Specification 
 The following transfers are to be made:
- Transfer 409,000 USDC to ens-ecosystem.pod.xyz
- Transfer 376,000 USDC, 40 ETH, and 52,300 $ENS to ens-metagov.pod.xyz
- Transfer 218,204 USDC and 35 ETH to ens-publicgoods.pod.xyz

Addresses for confirmation:
- 0x2686A8919Df194aA7673244549E68D42C1685d03 for ens-ecosystem.pod.xyz
- 0x91c32893216dE3eA0a55ABb9851f581d4503d39b for ens-metagov.pod.xyz
- 0xcD42b4c4D102cc22864e3A1341Bb0529c17fD87d for ens-publicgoods.pod.xyz

# Transactions 
 | Address                                    | Value  | Function | Argument | Value                                      |
| ------------------------------------------ | ------ | -------- | -------- | ------------------------------------------ |
| 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |        | transfer | to       | 0x2686A8919Df194aA7673244549E68D42C1685d03 |
|                                            |        |          | amount   | 409000000000                               |
| 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |        | transfer | to       | 0x91c32893216dE3eA0a55ABb9851f581d4503d39b |
|                                            |        |          | amount   | 376000000000                               |
| 0x91c32893216dE3eA0a55ABb9851f581d4503d39b | 40 ETH |          |          |                                            |
| 0xC18360217D8F7Ab5e7c516566761Ea12Ce7F9D72 |        | transfer | to       | 0x91c32893216dE3eA0a55ABb9851f581d4503d39b |
|                                            |        |          | amount   | 52300000000000000000000                    |
| 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |        | transfer | to       | 0xcD42b4c4D102cc22864e3A1341Bb0529c17fD87d |
|                                            |        |          | amount   | 218204000000                               |
| 0xcD42b4c4D102cc22864e3A1341Bb0529c17fD87d | 35 ETH |          |          |                                            |
