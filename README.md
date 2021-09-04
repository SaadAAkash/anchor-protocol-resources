# Anchor-Protocol-Resources

### Overview

- Anchor is a savings protocol offering low-volatile yields on Terra stablecoin deposits
- Defines a money market between a lender, looking to earn stable yields on their stablecoins, and a borrower, looking to borrow stablecoins on stakeable assets
- Aims to be a standard for savings accounts, by providing a stable APY between 18-20%
- Built by the South Korea-based Terraform Labs and launched on March 17, 2021
- Stripe for Savings
- A fitting answer to the search for a household savings product powered by cryptocurrency

### How It Works

![How Anchor Works](https://github.com/SaadAAkash/Anchor-Protocol-Resources/blob/master/resources/How-Anchor-Works.png)

- Anchor protocol serves as a money market between lenders and borrowers of stablecoins
- The lender can deposit their stablecoins on the platform for lending and earn interest on it
- The borrowers can borrow these stablecoins by providing stakeable assets as collateral. These assets are regarded as bonded assets, and currently, bLUNA is the only bonded asset that can be used as collateral
- The bonded asset is then locked up, and UST is borrowed against it at an LTV ratio defined by the protocol, which is currently a maximum of 40%. Anchor Protocol operates using a liquid staking mechanism. Staking rewards earned on bLUNA by borrowers are liquidated by the protocol into UST for depositors allowing them to earn target yield up to 20 %.

### Important Bits

- Anchor protocol's native and governance token is Anchor Token (ANC)
- Anchor protocol has a total supply of 1 billion ANC tokens and 40% of that has been set aside as borrower incentives for the next 4 years
- Anchor protocol is collateralized by tokenized stakes (bAssets) 
- The protocol defines the Anchor Rate, derived from the yield of the market’s highest-demand PoS assets, as the blockchain economy’s interest rate benchmark. 
- Anchor utilizes the block rewards of bAssets to offer depositors a stable return equal to the Anchor Rate
- Having bAssets from multiple PoS (Proof-of-Stake) blockchains, i.e. Ethereum 2.0., Polkadot, EOSIO, and Cardano etc., contributes to stabilize the interest rate
- The anchor rate is updated every epoch (3hrs) based on borrow demand and UST supply

### Difference with Moola Market

- No bonded asset concept in Moola. But there is Bonded Assets (bAssets) in Anchor
- Assets move from yield reserve to maintain 20% interest rate in Anchor
- Every borrower gets rewarded with ANC tokens

### Terra Ecosystem Overview

-  LUNA is the native staking token of the Terra protocol and foundational asset for the entire ecosystem
-  The Terra ecosystem includes several payment solutions and platforms:
  - CHAI e-wallet (Korea)
  - MemePay e-wallet (Mongolia)
  - Anchor savings protocol
  - Mirror synthetic asset protocol

## Risks
- Like all DeFi platforms, Anchor protocol has one major risk that users should be aware of and it is loan liquidation. This can happen when the value of the collateral falls below the value of the loan. This is common to all DeFi platforms so it is recommended to borrow at the LTV ratio of 45% or even lower while liquidation occurs at 60%.

## Q&A [(Handpicked from the Official Discord)](https://discord.gg/9aUYgpKZ9c)


<details>
<summary><strong>Can Anchor's deposit APY fluctuate between 18.xx% to 21.xx%, even if it's said to be fixed at a stable rate of 20%?</strong></summary>

Regarding the fluctuation between 19.5% and 20.5%, the APY is designed to stick within the threshold limit (19.5%) and target limit (20.5%), and these are both governance-controlled values, so they can be updated if the community votes on it. In fact it was recently changed by this proposal, from 18-20% to 19.5-20.5%.
When borrowing demand is low, Anchor subsidizes deposit yield using TerraUSD in the yield reserve. Subsidizations occur roughly every 3 hours (epoch) - user interactions between the 3-hour periods may slightly distort the deposit rate, hence the rate can be 18.xx% or 21.xx% and not exactly 19.5% and 20.5% respectively. </details>

<details>
<summary><strong>How does the block reward from PoS blockchain contribute to stabilize the interest rate?</strong></summary>
It's just a fixed rate right now.  There's been an announcement some type of periodic interest rate adjustment will be implemented that incorporates things like staking return, but the TLDR for the current version of Anchor is that it doesn't
  
  Updated on 02-09-2021: [Ref](https://discord.com/channels/816973230526693396/816973230979153931/882860291992473640)
</details>

<details>
<summary><strong>Why does Anchor protocol require borrowers to put bonded Luna as collateral but not Luna as the same?</strong></summary>
When you bond your Luna, you are staking it with a whitelisted validator, and then providing that as collateral allows the protocol to receive the staking rewards. Just providing Luna wouldn't generate any rewards.
</details>

<details>
<summary><strong>Why doesn't it allow you to provide Luna and then just auto-stake it? </strong></summary>
I assume in order to keep it more decentralized, in that a user needs to specify with whom to stake it with. I think it’s just to separate the fact that you don’t own the Luna once it’s been provided as collateral to avoid confusion.
</details>

<details>
<summary><strong>What is ANC buy back?</strong></summary>
Fees from anchor are used to buy ANC on terraswap and these are then distributed to ANC stakers. So, the more activity there is on anchor, the more anc is bought by the system and staking rewards increase
</details>

### References/Links

- [Web Dashboard](https://app.anchorprotocol.com/)
- [Docs](https://docs.anchorprotocol.com/)
- [Whitepaper](https://anchorprotocol.com/docs/anchor-v1.1.pdf)
- [Medium - Anchor Protocol: A Savings Protocol Offering Up To 20% APY](https://medium.com/everstake/anchor-protocol-for-beginners-how-to-get-started-5b19f54ced6d)
- [Medium - Terra Ecosystem Overview: A Guide for Newcomers](https://medium.com/everstake/terra-ecosystem-overview-a-guide-for-newcomers-1d52b717c429)
- [How to Get Started with Anchor Protocol: A Step-By-Step Guide and Yield Farming Strategies](https://medium.com/everstake/how-to-get-started-with-anchor-protocol-a-step-by-step-guide-and-yield-farming-strategies-f9a94f83ce1f)
