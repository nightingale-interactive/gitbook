# MARD

MARD is the currency of opulence — the coin of the Marmalade Kingdom, and the one Lady Amberworth counts twice. It is also the token that makes the Meta-land economy run.

#### **At a Glance:**

| Field          | Value                                                                                                         |
| -------------- | ------------------------------------------------------------------------------------------------------------- |
| Name / Symbol  | Marmalade Token / MARD                                                                                        |
| Type           | Utility currency                                                                                              |
| Standard       | ERC-20, 18 decimals                                                                                           |
| Network        | Immutable zkEVM                                                                                               |
| Contract       | 0xD9aDf2E6CDCD25882d7BCCcc54b58e118Ccf3da8                                                                    |
| Maximum supply | **None** — MARD is a dynamic-supply token                                                                     |
| Live supply    | [View on Immutable Explorer](https://explorer.immutable.com/token/0xD9aDf2E6CDCD25882d7BCCcc54b58e118Ccf3da8) |

{% hint style="info" %}
**Why there is no supply table here:** MARD has no fixed cap and no emission schedule. It is minted as gameplay rewards and removed by sinks, so any figure printed in this guide would be stale by the time you read it. The live on-chain figure is always available on the block explorer.
{% endhint %}

{% hint style="info" %}
Note also that the explorer counts only MARD that players have withdrawn to their wallets. A substantial amount of MARD sits inside game accounts and has not been withdrawn. On-chain supply therefore rises when players withdraw and falls when they deposit — it measures withdrawal activity, not the size of the whole economy.
{% endhint %}



#### **What MARD Is For:**

| Use                    | Description                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| MARD Shop              | Purchase Rainbow Beanz, premium goods, and seasonal items from Lady Amberworth's shelves |
| Ticket Betting         | Buy race tickets and wager on sheep races with no betting cap                            |
| Rainbow Beanz exchange | Convert MARD into Rainbow Beanz on the official website                                  |
| Crafting & upgrades    | Consumed as a material cost in crafting and item recipes                                 |

#### **How MARD Enters Circulation**

| Source                 | Description                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------- |
| Selling wool           | Shear your NFT sheep and sell the wool to Madge. Paid out of the **Wool Pool**     |
| Ticket race payouts    | 7% of all wagers is distributed to placing sheep. Paid out of the **Betting Pool** |
| Achievements & rewards | Milestone and event rewards                                                        |

Only **NFT sheep** produce wool that can be sold for MARD. Non-NFT sheep can still be raised and raced, but their wool does not convert to token rewards.



#### **Tokenomics v2 — The Seasonal Pool Cycle**

MARD is not emitted on a fixed schedule. Since **Tokenomics v2 (December 2023)**, player spending funds player rewards, one season at a time.

At the close of each season, all MARD collected through MARD Shop sales is settled as follows:

```jsx
MARD Shop revenue (100%)
├── 10%  →  Burned permanently
└── 90%  →  MARD Pool for the next season
             ├── 45%  →  Wool Pool     (buys players' wool)
             └── 45%  →  Betting Pool  (pays ticket race dividends)
```

**Wool Pool:** Allocated across sheep rarities, and distributed evenly among sheep of the same rarity and NFT type. The more wool sold against the same pool, the smaller each payout — the pool does not grow to meet demand.

**Betting Pool:** Divided evenly across the season's races, based on the pool size measured at the start of the season.

**Carry-over:** Any pool funds left unspent at season's end roll into the following season.



#### **Two consequences are worth stating plainly:**

1. **Rewards are capped by spending, not by time.** If MARD Shop sales are low, the next season's pools are small. Farming harder does not increase the pool — it only divides the same pool among more wool.
2. **The 10% burn is permanent.** Every season with shop activity removes MARD from total supply for good.

#### **Why v2 Exists:**

The original 2022 model minted MARD through NFT staking — a standard GameFi emission design, and one that inflated faster than the game could absorb. Sheep Racing was introduced in late 2022 as a sink, and a mining halving followed in early 2023 as an emergency brake. Neither solved the underlying problem: emissions were disconnected from real demand.



Tokenomics v2 inverted the relationship. Instead of minting first and hoping sinks catch up, the game now collects first and pays out of what it collected.

{% hint style="info" %}
**Current status.** Tokenomics v2 is the active MARD model. As the game settles into its new home on Immutable zkEVM, we are reviewing how the seasonal cycle should evolve, and any changes will be documented here.
{% endhint %}



#### **Migration History**

MARD originated on Klaytn/Kaia and moved to Immutable zkEVM as part of the network migration completed in 2026. Balances were carried across through the SHOP deposit and withdrawal flow, and the Immutable contract above is now the sole canonical MARD contract. Contracts on all previous networks are retired.
