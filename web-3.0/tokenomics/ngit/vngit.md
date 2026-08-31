# vNGIT

vNGIT is your voice in Meta-land. You cannot buy it, and you cannot trade it — you earn it by keeping the market for Sheepfarm's tokens alive.

#### **At a Glance:**

| Name              | vNGIT (voting credit)                                                                    |
| ----------------- | ---------------------------------------------------------------------------------------- |
| Purpose           | DAO voting power                                                                         |
| How to earn       | Provide **full-range** liquidity to the **NGIT–MARD** pool on QuickSwap, then Claim once |
| Rate              | **7 vNGIT per unit of liquidity, per week**                                              |
| Distribution      | Weekly, every **Monday**, by wallet snapshot                                             |
| Cost to vote      | **1 vNGIT per vote**                                                                     |
| Balance behaviour | Accumulates; spent when voting                                                           |
| Transferable      | No                                                                                       |
| Where to use      | **DAO** menu on the official website                                                     |

#### **How to Earn vNGIT:**

vNGIT rewards liquidity, not holding. Simply keeping NGIT in a wallet earns nothing.

1. **Provide full-range liquidity.** Deposit NGIT and MARD into the NGIT–MARD pool on QuickSwap (Immutable zkEVM), with the price range set to **full range (0 to ∞)**. QuickSwap issues your position as a **liquidity provider NFT** held in your wallet.
2. **Claim once.** Go to **DAO → Earn** on the website and press **Claim**. This registers your wallet for weekly distribution. You only need to do this once — not every week.
3. **Get paid every Monday.** Each Monday, the system checks your wallet. If it still holds a qualifying liquidity provider NFT, vNGIT is credited automatically at **7 vNGIT per unit of liquidity**.
4. **Track your history.** **DAO → Earn** shows your current LP status and your complete vNGIT distribution history.

{% hint style="info" %}
**Full range only.** QuickSwap lets you concentrate liquidity within a narrow price band. Those positions earn trading fees, but they do **not** qualify for vNGIT. Only positions covering the entire price range (Min 0, Max ∞) are counted at the Monday snapshot. Set your range accordingly before you deposit — an existing narrow position cannot be widened, only closed and reopened.
{% endhint %}



#### **How Much Will I Earn?**

A full-range position's liquidity is the geometric mean of the two token amounts it holds:

**liquidity  =  √(NGIT amount × MARD amount)weekly vNGIT  =  liquidity × 7**

Because NGIT and MARD trade close to parity, a balanced position holding roughly the same amount of each token carries roughly that amount of liquidity. In practice:

| Position                  | Approx. liquidity | Weekly vNGIT | Votes per week |
| ------------------------- | ----------------- | ------------ | -------------- |
| 100 NGIT + 100 MARD       | \~100             | \~700        | \~700          |
| 1,000 NGIT + 1,000 MARD   | \~1,000           | \~7,000      | \~7,000        |
| 10,000 NGIT + 10,000 MARD | \~10,000          | \~70,000     | \~70,000       |

The figures above assume a roughly 1:1 NGIT/MARD price. If the price moves away from parity, use the formula.

{% hint style="info" %}
**The snapshot is a moment, not an average.** Distribution is based on what your wallet holds at the snapshot time on Monday. If you remove liquidity before the snapshot, you receive nothing for that week — even if you provided liquidity for the previous six days.
{% endhint %}



#### **How to Use vNGIT:**

Today, vNGIT has one function: **Weather Voting**.

Weather changes how races run, and the community decides the forecast.

| Weather    | Effect on racing sheep                |
| ---------- | ------------------------------------- |
| **Sunny**  | +12% Speed, +12% Spirit               |
| **Rainy**  | −10% Speed, +20% Balance              |
| **Snowy**  | −10% Stamina, +30% Power              |
| **Stormy** | −16% Speed, −16% Balance, +24% Spirit |

Open **DAO → Vote** to see active polls for upcoming races, cast your vote with vNGIT, review the running tally for each condition, and check your voting history.



Because different weather favors different attribute builds, weather voting is a genuine strategic lever — a flock trained for Power has every reason to vote for snow.



#### **How Voting Weight Works**

**One vNGIT casts one vote, and votes are weighted.** You are not limited to a single vote per poll — you may commit as much of your balance to one weather condition as you like. A holder spending 5,000 vNGIT on Snowy adds 5,000 to that condition's tally.



Your balance accumulates week over week and never expires. There is no reset, so vNGIT can be saved for a race that matters and spent all at once.

|                | Effect                                 |
| -------------- | -------------------------------------- |
| Cost per vote  | 1 vNGIT                                |
| Votes per poll | Unlimited, up to your balance          |
| Weighting      | Linear — 1 vNGIT = 1 vote in the tally |
| Expiry         | None                                   |

{% hint style="info" %}
**Why liquidity providers?** Weather voting has a direct effect on race outcomes, and race outcomes have a direct effect on MARD payouts. Tying voting power to liquidity provision means the people steering the game are the same people carrying market risk in it.
{% endhint %}
