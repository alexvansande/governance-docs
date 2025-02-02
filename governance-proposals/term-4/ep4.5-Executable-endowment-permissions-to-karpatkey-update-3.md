---
description: This proposal introduces new actions and strategies to the Endowment with the aim of enhancing diversification and adapting to current market conditions. Notable additions include ETH-neutral strategies involving Liquid Staking Protocols and established Money Markets.
---

# [EP 4.5] [Executable] Endowment permissions to karpatkey - Update #3

| **Status**            | Pending                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Discussion Thread** | [Discuss](https://discuss.ens.domains/t/ep-4-5-executable-endowment-permissions-to-karpatkey-update-3/18036)                                                                                                |
| **Votes**             | [Active](https://agora.ensdao.org/proposals/15706104363492914432572227540113855373051896881975394006732444538096386655538)                                                                                                                                     |


# Motivation

Following the successful approval of [E.P. 4.2](https://www.tally.xyz/gov/ens/proposal/10686228418271748393758532071249002330319730525037728746406757788787068261444),  the second tranche of the Endowment was funded with 16,000 ETH. Community feedback during the E.P. 4.2 voting window indicated a desire to reduce exposure to Lido due to concerns about centralization risks in the network. While diversifying ETH-neutral holdings was already underway, the need for further diversification and divestment from Lido became clear during [community discussions](https://discuss.ens.domains/t/4-2-executable-fund-the-endowment-second-tranche/17743) and the last [Meta-gov call](https://discuss.ens.domains/t/metagov-working-group-weekly-meeting-11am-et-tuesday/15981/43#h-2-endowment-discussion-karpatkey-steakhouse-10) before the vote's closure. Consequently, karpatkey and @steakhouse proposed a 20% cap on Lido's maximum allocation within the ETH-neutral portfolio, set to be achieved by month-end. This proposal's goal is to introduce new strategies for deploying the remaining 80% of the funds as well as other minor maintenance actions.


# Specification

Permissions to be added in this proposal:



1. Deposit ETH on Compound v3;
2. Deposit ETH or WETH on AAVE v3;
3. Deposit ETH or WETH on Spark Protocol;
4. Stake (and unstake) ETH on Stader;
5. Stake (and unstake) ETH on Ankr;
6. Removal of CowSwap permissions;
7. Removal of SushiSwap permissions*;
8. Addition of an alternative getReward() for Aura pools;
9. Swaps:
    1. rETH &lt;> WETH on Balancer;
    2. rETH &lt;> WETH on Uniswap v3;
    3. ankrETH &lt;> wstETH on Balancer;
    4. ETHx &lt;> WETH on Balancer;
    5. ankrETH &lt;> ETH on Curve;
    6. ETHx &lt;> WETH on Pancake Swap

**edited on 2023-11-03*

## Auditing Process

We are releasing an updated version of the ["Preset Permissions - ENS Endowment''](https://docs.google.com/document/d/1Ker_TkBJV0xmQ9Li9HB-vtdlpx1vEeVEQwpIH6WoK0o/edit?usp=sharing) document, highlighting all permissions granted to karpatkey, with proposed additions marked in green and revocations in red. We encourage community members with technical expertise to review and provide feedback on the preset update [payload](https://gist.github.com/santinomics/5b43dee4839d74e2c593ac9e7c7d1d3d).

In the auditing realm, significant progress has been made, with a [new version](https://zodiac-roles-1h9v0miw9-gnosis-guild.vercel.app/gor%3A0x74F819Fa1D95B57a15ECDEf9ce5c779C1bD6cc8A/roles/test-role/diff/4Iq1jdNbLbCBKmLAKciGaDQANiHStkCqFvJJ5KWQc) of the Zodiac Roles Modifier app developed by Gnosis Guild. When fully operational, this app will allow users to input a payload and check the before-and-after status of permissions presets, enhancing the auditing process. 

Furthermore, we're actively engaged in collaborative efforts with potential partners to create a user-friendly audit report, enhancing openess for all stakeholders involved in the process. In our commitment to transparency, we're taking an additional step by offering a [self-audit report](https://hackmd.io/@karpatkey/Hy2TyPdfp). This report sheds light on our internal procedures for assessing proposed permissions and changes, providing further insight into our practices.
# Transactions
<!-- The transactions section describes all the calls that should be encoded in the onchain version of this proposal. Use the table below as a starting point. -->
<table>
    <tr>
        <th>Address</th>
        <th>Value</th>
        <th>Function</th>
        <th>Argument</th>
        <th>Value</th>
    </tr>
    <tr>
        <td rowspan=2>Address or ENS name of target</td>
        <td rowspan=2>Value to send (ETH)</td>
        <td rowspan=2>Function identifier</td>
        <td>First arg</td>
        <td>First value</td>
    </tr>
    <tr>
        <td>Second arg</td>
        <td>Second value</td>
    </tr>
</table>
