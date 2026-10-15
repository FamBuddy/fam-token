# $FAM Whitepaper

**We're all fam here. No whales, just family.**

|Item|Detail|
|---|---|
|Version|v3.0|
|Last Updated|October 14, 2026|
|Status|Community Release|
|Official Channel|All official announcements are published on the official X account: [@Fam_Buddy](https://x.com/Fam_Buddy)|

---

## Table of Contents

1. Abstract
2. Vision: A Truly Fair Community
3. The Problem: Whale Dominance in Meme Coins
4. What Is $FAM?
5. Tokenomics
6. Weekly Lottery Mechanism
7. Cryptographic Fairness
8. Prize Pool Rules
9. Fairness Commitments
10. Roadmap
11. Risk Disclosure
12. Disclaimer

---

## 1. Abstract

$FAM is a community-driven meme coin built on Solana blockchain. We believe the spirit of cryptocurrency belongs to every participant — not a handful of whales.

Through a weekly fair lottery, $FAM directs 50% of all project revenue into a fully public prize pool address, used to buy $FAM and pay winners directly; the other 50% funds project operations. Every token enters the liquidity pool at launch — 0% team allocation, verifiable on-chain. Supply is fixed. Our interests are fully aligned with the community.

### The Mechanism at a Glance

|Stage|Rule|
|---|---|
|Revenue Source|Project revenue generated from every trade, collected in SOL|
|Pool Source|50% of all project revenue, routed automatically to a public pool address|
|Reward Form|$FAM — purchased by the pool with SOL on the open market|
|Eligibility|Holding value ≥ $100 at snapshot; one person, one vote|
|Winner Selection|sort_key = SHA256(address + SALT); top 3 by ascending value|
|Prize Split|3 winners split the entire pool equally|
|Payout Window|Within 5 days of results publication|
|Gas Coverage|A portion of SOL reserved in the pool, dedicated to payout fuel|

---

## 2. Vision: A Truly Fair Community

The original promise of crypto was decentralization — finance for everyone, not just the elite.

But today, most meme coins are broken: team wallets hold 20–50% of supply and dump on retail. Whales manipulate price while followers chase pumps. The people who believed in the mission get rekt.

**$FAM changes that.**

Our commitments:
- 100% of supply into the liquidity pool — 0% team allocation
- Fixed supply — no inflation, ever
- 50% of all project revenue routed automatically into a public prize pool address (paid out in $FAM)
- One person, one vote — shrimp and whales on equal footing

---

## 3. The Problem: Whale Dominance in Meme Coins

|Status Quo|Consequence|
|---|---|
|Team reserves 20–50% of supply|Dump at the top, retail bags|
|Concentrated whale holdings|Price controlled by a few, followers chase|
|Opaque mechanics|Rigged draws, trust collapses|
|Misaligned incentives|Rug pulls become routine|

$FAM is designed from the ground up to fix these.

---

## 4. What Is $FAM?

|Item|Detail|
|---|---|
|Coin Name|FamBuddy|
|Ticker|$FAM|
|Blockchain|Solana|
|Supply|Fixed total — no inflation, ever|
|Circulation|100% — all tokens enter the liquidity pool at launch, 0% team allocation|
|Revenue Split|50% of all project revenue to the public pool / 50% to project operations|
|Reward Form|**$FAM tokens** (purchased by the pool with SOL)|

### Brand Ethos

> **"We're all fam here. No whales, just family."**

**The project is FamBuddy, the token is $FAM, the community is the Fam.**

Three faces of one idea: **Fam** is the culture — that "gm fam" greeting everyone says. **Buddy** is the friend who shows up with you. **$FAM** is the receipt you hold. The name grows out of crypto's daily greeting, carrying community DNA from day one.

**Why $FAM?**
- **Short**: A 3-letter ticker. Instantly memorable.
- **Friendly**: Say it out loud and it already feels like "one of us".
- **Neutral across languages**: "Buddy" reads as pal/mate in English-speaking markets and stays friendly everywhere else.
- **Belonging**: Hold $FAM and you're part of the Fam.

**About Buddy the character**

The mascot is **Buddy the Rabbit** — a navy, astronaut-styled designer-toy rabbit with gold headphones, crescent-moon eyes, `Buddy` embroidered on its chest, and a single gold coin in its paw engraved with `FAM`.

It isn't decoration. It's the personification of the mechanism:

- **It holds a coin — but a small one.** The prize pool is real and finite, not an unlimited promise drawn on a poster.
- **The coin says FAM.** A reminder of who this thing belongs to: everyone.
- **It stands still.** Same rules every week, public ledger, anyone can recompute the draw.

$FAM is not a speculation tool. It's a community. Every holder is part of the Fam — we win together, we build together, we grow together. **No whales, just family.**

---

## 5. Tokenomics

### 5.1 Supply Model
- **Fair launch**: 100% of supply enters the liquidity pool at launch — no team allocation, verifiable on-chain
- **Fixed total supply**: Circulating supply is constant from day one — no inflation
- **Team revenue**: The only income stream is 50% of all project revenue — directly tied to community activity

### 5.2 Revenue Allocation

Every trade on $FAM generates project revenue. That revenue is split 50/50 — fixed and publicly committed:

| Allocation | Share | Purpose |
|---|---|---|
| Community prize pool | 50% | Funds the weekly $FAM lottery |
| Project operations | 50% | Development, marketing, maintenance |

```
Project revenue (collected in SOL)
  ├── 50% → Public prize pool address (routed automatically by contract)
  │         ├── Majority → used to buy $FAM on the open market → distributed to winners
  │         └── Minority → reserved in SOL → gas fuel for distributing $FAM
  └── 50% → Project operations (development, marketing, maintenance)
```

**The 50/50 split is fixed and publicly committed.** The prize pool wallet is a separate public address, so anyone can check its SOL balance and every incoming transfer on a block explorer at any time — no one has to take the project's word for it. The routing happens in contract code, so there is no window in which the team could receive the funds and then decide how much to pass on.

**Why this design?**
- Team revenue is directly tied to trading volume — the only way the team earns is if the community is active
- This means the team has the strongest possible incentive to build community, drive growth, and create long-term value
- The team literally cannot "dump" — we don't hold any tokens
- Prizes are paid in **$FAM**: winners receive the project's own token, tying rewards directly to community consensus — we grow the pie together

---

## 6. Weekly Lottery Mechanism

### 6.1 Eligibility
- Hold $FAM tokens at the snapshot time
- Every wallet address is automatically entered — no sign-up required

### 6.2 One Person, One Vote
|Item|Rule|
|---|---|
|Threshold|Holding value **≥ $100 USD**|
|Entries per Address|**1 ticket per eligible address**|
|Core Principle|**Equal for everyone — one person, one vote**|

**Examples:**
- $100 holding → 1 ticket
- $1,000 holding → 1 ticket
- $100,000 holding → 1 ticket

Whether you're a shrimp or a whale, your odds are identical. All eligible addresses are ranked by one cryptographic rule; the top 3 win (see 6.4).

### 6.3 Snapshot Rules
|Item|Rule|
|---|---|
|Snapshot Time|Every **Sunday 23:59 UTC**|
|Snapshot Content|All holder addresses and their token balances|
|SALT Lock|The week's block hash is recorded as the cryptographic sort seed|
|Public Disclosure|Complete sorted list and winner list published to the entire community|

### 6.4 Winners
|Item|Rule|
|---|---|
|How Winners Are Determined|Addresses are sorted by sort_key **value in ascending order** — the **top 3 addresses win**|
|Minimum Threshold|Token live for **≥ 7 days** AND at least **100 eligible addresses** (holding ≥ $100); below threshold the draw is postponed and the pool rolls over (see 6.6)|
|Prize Split|3 winners split the entire pool equally|
|Reward Form|**$FAM tokens** — purchased by the pool with SOL and sent directly to winners' wallets|

**The sort is the draw**: SALT is locked at snapshot time, and the SHA256 ordering is deterministic — no additional random selection step is needed. Anyone can recompute the exact same winner list from public data.

### 6.5 Weekly Timeline (UTC)

|Time|Milestone|Details|
|---|---|---|
|Sunday 23:59|Snapshot + SALT lock|Record all holder addresses, balances, and the week's block hash|
|Monday 00:00–12:00|Sorting & pool funding|Compute sort_key for every address and sort by value — top 3 win; fund the pool (spend the SOL held at the public pool address to buy $FAM back into that same address)|
|Monday 12:00–24:00|Full disclosure / postponement notice|If threshold met: publish the complete sorted list, the 3 winners, pool $FAM balance, and SOL gas reserve to the entire community; if not: publish a postponement notice and roll the pool over|
|Within 5 days of announcement|Payout|Pool address distributes $FAM to winners (consuming reserved SOL gas); every transaction published on-chain|

**Why this order?**
- **Fund first, pay later**: The pool balance is public on-chain before any prize is sent — independent of the winner list, and every payout transaction is traceable
- **A full night between snapshot and disclosure**: Anyone has ample time to verify the snapshot data; the sort and winner list are fully recomputable from public data
- **A 5-day payout window**: A buffer between announcement and payout — time to confirm winners' receiving addresses and handle gas or on-chain edge cases, ensuring every prize arrives; the pool balance stays publicly verifiable until payout completes

### 6.6 Draw Conditions & Postponement Rules

**Draw conditions (both must be met)**

|Condition|Rule|
|---|---|
|Time Since Launch|Token live for **≥ 7 days** — ensures a complete accumulation window for the community and a meaningful first prize pool|
|Holding Addresses|At least **100 eligible addresses** (holding value ≥ $100) at snapshot|

**First edition timing**
- First snapshot: the first Sunday 23:59 UTC after both conditions are met (i.e., the first Sunday after the token has been live for 7 days)
- First winner list: published to the entire community the following Monday, 12:00–24:00 UTC
- First payout: completed within 5 days of publication — identical rules to every regular cycle
- Example: if the token goes live on Friday, October 16, the first snapshot is Sunday, October 25 at 23:59 UTC, the first winner list is published on Monday, October 26, and the first payout completes by October 31

**If conditions are not met**
- No draw that week — but a **postponement notice must still be published on Monday**, stating the current eligible address count, the gap to threshold, the rolled-over pool size, and next week's snapshot time
- Pool rollover: the week's $FAM prize and SOL fuel reserve roll over in full to the next edition until the threshold is met — postponement is not a stoppage; the pool only grows bigger

---

## 7. Cryptographic Fairness

### 7.1 Why Cryptography?

The biggest problem with traditional lotteries is that the house can rig the result. We eliminate that with math.

### 7.2 Sorting & Winner Selection Algorithm

```
Step 1: Lock SALT at snapshot
  Take the latest Solana block hash at Sunday 23:59 UTC as SALT
  (On-chain, public — the team cannot predict or alter it)

Step 2: Generate sort key for each address
  sort_key(Ai) = SHA256( Ai + SALT )
  Compute a cryptographically random sort value for each holding address

Step 3: Sort by sort_key value in ascending order
  Rank 1 (smallest value) → WINNER
  Rank 2 → WINNER
  Rank 3 → WINNER
  Rank 4 and beyond → not selected
```

### 7.3 Why Is This Fair?

|Challenge|Answer|
|---|---|
|"Did you just make up the ordering?"|Ordering is determined by SHA256 math — anyone can re-verify|
|"Could you choose a favorable order?"|SALT is a future block hash — impossible to predict in advance|
|"How are winners produced?"|Top 3 by sort_key value in ascending order — a unique rule, a deterministic result|
|"What if you changed it after the fact?"|SALT is public at snapshot time — verifiable on-chain|

### 7.4 Sybil Protection

$FAM defends against Sybil attacks with a four-layer mechanism: barrier, technology, oversight, and rules.

|Layer|Mechanism|Details|
|---|---|---|
|Barrier|≥ $100 holding|Every address requires a genuine position — the more sock puppets, the more capital tied up, so farming costs scale linearly|
|Tech|Automated on-chain tracing|On-chain scripts automatically scan the SOL funding sources of snapshot addresses, flagging suspicious clusters: same-source transfers, batch creation at the same time, identical behavioral patterns|
|Oversight|Full disclosure + community monitoring|The complete sorted list is public and verifiable — anyone can submit on-chain evidence; the team verifies, disqualifies, and publishes the rationale|
|Rules|Traceability & voiding|Once a sock puppet is confirmed, the prize is voided and rolls to the next ticket|

Together, these mechanisms raise the cost of Sybil attacks and significantly increase exposure risk — every sock puppet ties up ≥ $100 of real capital and remains subject to retroactive disqualification at any time.

---

## 8. Prize Pool Rules

### 8.1 Pool Source and Flow

```
Flow path:
Project revenue (collected in SOL on every trade)
  └── 50% → Public prize pool address
            ├── Majority of SOL → buy $FAM on the open market → back to the public prize pool address
            └── Minority of SOL → gas reserve (fuel backup)
```

- **Rewards are $FAM; the project revenue is collected in SOL**: **50% of all project revenue** is routed automatically by contract into the public prize pool address; the remaining 50% funds project operations
- The majority of the pool's SOL is used to buy **$FAM** on the open market. The purchased $FAM is transferred in full to the public prize pool address and serves as that week's prize
- Once results are published, the pool address distributes **$FAM** to the 3 winners
- A minority of the pool's SOL is kept as a **gas reserve**, dedicated to covering the gas cost of distributing $FAM

### 8.2 SOL Gas Reserve

- Transferring $FAM (an SPL token) on Solana consumes **SOL as gas fuel**
- If a winner's wallet has not yet opened a $FAM token account, the first transfer also requires paying the token account creation fee
- Therefore, the pool **must reserve a portion of SOL** as backup: ensuring sufficient gas for every weekly payout, so the distribution process runs smoothly and never stalls
- This SOL reserve is used for gas only — never paid out, never reallocated — and is accounted for separately from the $FAM prize

### 8.3 Transparency commitment

#### Public prize pool address

|Item|Detail|
|---|---|
|Prize pool wallet|`56jR6icH3eQVjNachZBRbAttHQxRRXZ3e8S1i8AhcF1A`|
|Explorer|`https://solscan.io/account/56jR6icH3eQVjNachZBRbAttHQxRRXZ3e8S1i8AhcF1A`|
|Asset|SOL (received, then used to buy $FAM)|
|Allocation|50% of all project revenue, routed automatically by contract|
|Allocation status|Set once, permanently locked, not changeable|

**Anyone can verify this independently at any time, without taking the project's word for anything:**

- Every incoming transfer to that address can be checked one by one on a block explorer; the source is project revenue
- The SOL balance of that address reflects the pool's currently available funding
- The weekly $FAM purchase and the payouts to the 3 winners are all on-chain and viewable
- The address is **separate from the operations wallet**: operating spend and community prizes are physically isolated, so there is no window in which fees are pooled together and a split is decided later

> **On the initial balance**: the pool wallet needs a small amount of SOL to pay for its first on-chain transaction (gas). That is setup cost, not pool income, and is noted separately in each week's disclosure.

#### Weekly disclosure contents

Before each draw, the project announces on the community channel: (1) the current prize pool amount, (2) the reward amount to be distributed this round, and (3) the reserved amount (gas reserve).

Each week the project posts the following on the official X account, with explorer screenshots:

1. The pool address's weekly SOL income and closing balance
2. The transaction hash of the $FAM purchase
3. The complete sorted list and the 3 winning addresses
4. The payout transaction hashes with confirmation

---

## 9. Fairness Commitments

$FAM commits to these principles forever:

1. **One person, one vote**: Every address holding ≥ $100 gets exactly 1 ticket — shrimp and whales are equal
2. **Cryptographic sorting**: Ticket assignment is determined by SHA256 — the team cannot manipulate the order
3. **On-chain randomness**: The sort seed SALT comes from an on-chain block hash — the team cannot predict or tamper with it
4. **Fair launch**: 100% of supply in the pool — 0% team allocation, verifiable on-chain
5. **Fixed supply**: No inflation — your holding never gets diluted
6. **Full transparency**: All rules, sorted lists, and transactions are publicly verifiable

---

## 10. Roadmap

|Phase|Goal|
|---|---|
|**Phase 1: Launch**|Deploy token, establish official community channels, activate weekly lottery|
|**Phase 2: Growth**|Reach 1,000 holders, expand community reach, grow weekly prize pools|
|**Phase 3: Maturity**|Stable volume, growing prize pools, stronger fairness narrative|
|**Phase 4: Evolution**|Explore on-chain automation contracts, expand community features|

---

## 11. Risk Disclosure

- Cryptocurrency investments are extremely high risk — prices are highly volatile
- Meme coin projects may go to zero at any time
- Past performance does not guarantee future results
- Only invest what you can afford to lose

---

## 12. Disclaimer

This whitepaper is for informational purposes only and **does not constitute financial advice**.

$FAM is a community entertainment project. No returns are promised. Cryptocurrency investment risk is extreme. Past performance does not indicate future results.

**Not for US persons.** This project is not directed at users in the United States.

Participation means you understand and agree to all terms.

---

*We're all fam here. 🫂*
