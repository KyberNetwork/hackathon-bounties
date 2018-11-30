# Hackathon Bounties
We were blown away by the projects that integrated with Kyber at ETHSF, and are excited to see what ETHSG can bring!

<!-- Table Of Contents-->
[What is Kyber?](#what-is-kyber)<br>
[What can you #BUIDLwithKyber?](#what-can-you-buidlwithkyber)<br>
[Bounties](#bounties)<br>
[Prizes](#prizes)<br>
[Judging Criteria](#judging-criteria)<br>
[Contacting Us](#contacting-us)

## What is Kyber?
Kyber is a fully on-chain protocol that powers decentralised token swaps for wallets, applications and platforms. It can be used in 4 major ways.

### 1. End User Token Swaps
The simplest use-case that allows users to easily swap from any ERC20 token to another, including Ether. This functionality can be found in popular wallets like MyEtherWallet and imToken, and on websites such as KyberSwap and Easwap.

### 2. Trading Integrations
We allow for arbitrage bots to take advantage and profit off market inefficiencies, either by directly interacting with our smart contracts, or through our recently announced [trading API](https://blog.kyber.network/introducing-the-kyber-trading-api-b30550645b74).

### 3. Payments
Users can purchase virtual collectibles in the form of non-fungible tokens (NFTs) with any supported ERC20 token on Kyber. More broadly, any platform can widen their payment options from just Ether to include ERC20 tokens as well. Examples include Etheremon and Peepeth.

### 4. Finance
A number of financial DApps use Kyber as an on-chain price feed. The liquidity provided by Kyber’s reserves are also used for index fund rebalancing, as one can see in Betoken and MelonPort.


## What can you #BUIDLwithKyber?

### Instant token swaps
Embed simple and atomic ERC20 <-> ERC20 token swaps in your application.

### Single Step Payments
Expand your payment options for your users by accepting not just ETH, but ERC20 tokens too. Empower your users with the freedom of choice in pay in their favourite tokens. [Peepeth](https://peepeth.com/a/crowdfunding) and [Etheremon](https://hackernoon.com/etheremon-integrates-with-kybers-on-chain-liquidity-protocol-a-new-payment-solution-for-ccbb36dfd595) are but some examples.

### On-chain Fund Rebalancing
Achieve seamless liquidation of assets for immediate rebalancing of portfolios in a single transaction. Take a look at [b0x](https://medium.com/@b0xNet/kyber-bzx-b6f5330289a6) and [Betoken](https://medium.com/betoken/6-primordial-reasons-to-build-a-decentralized-hedge-fund-with-kyber-1bbb3ed6a4d9) for a glimpse of what is possible!

### Arbitrage Programs
Take advantage of market inefficiencies, since prices are not always the same across different price discovery venues, especially between off-chain and on-chain prices. Help improve price equilibrium across the market whilst profiting from it!

If you need more ideas on what you can build, take a look at the bounties below!

## Bounties
### [Simple Swap Interface on IPFS](https://github.com/KyberNetwork/hackathon-bounties/issues/9)
Create a static website hosted on IPFS that interacts directly with Kyber's smart contracts via Infura. In other words, the website is a simple interface that allows any user to easily swap between ERC20 tokens and Ether.

### [Advanced Trading Orders](https://github.com/KyberNetwork/hackathon-bounties/issues/10)
Consider allowing for more complex trade orders to be executed using Kyber. For example, a user can create and sign a limit order. An application can be built to collate these orders, and execute them on Kyber when the price reaches the desired limit.

### [Historical Data Tool](https://github.com/KyberNetwork/hackathon-bounties/issues/11)
Create an interface or API where users can query historical price and volume trade data of the different tokens supported on Kyber. This data should be cached to quicken access by 3rd party applications who require such data.

### [Set Protocol Issuance Relayer](https://github.com/KyberNetwork/hackathon-bounties/issues/12)
Build an issuance relayer that taps on liquidity provided from Kyber’s reserves and from other liquidity providers like 0x. This enables users to obtain competitive prices for their Set, while also providing savvy market takers with arbitrage opportunities.

### [Collateral Liquidation On-Chain](https://github.com/KyberNetwork/hackathon-bounties/issues/1)
Lending platforms such as ETHLend, Dharma and Bloqboard allow for ERC20 tokens to be put as collateral. In the event of a loan default, allow the lender to perform liqudation of collateral into the token of his choice whilst withdrawing it into his account.

### [Off-Chain Virtual Orderbook Relayer](https://github.com/KyberNetwork/hackathon-bounties/issues/2)
Reconstruct an orderbook by extracting information from Kyber's reserves (denoted as on-chain orders), while allowing users to create off-chain orders. It'll be interesting to see how settlement occurs between an on-chain and off-chain order.

### [Integration with MakerDAO's Collateralized Debt Position (CDP)](https://github.com/KyberNetwork/hackathon-bounties/issues/3)
The creation of a CDP requires ETH, while its closing requires DAI and MKR tokens respectively. Furthermore, the creation and closing process is rather tedious and complicated, where one has to understand the mechanism well. Consider simplifying the process to make it user-friendly and easy to do in a single step.

### [Arbitrage Programs](https://github.com/KyberNetwork/hackathon-bounties/issues/4)
Make a DApp that takes advantage of market inefficiencies between Kyber and another venue! Take the bounty, keep the profit!

## [Open Category](https://github.com/KyberNetwork/hackathon-bounties/issues/5)
If you have your own idea that integrates with our protocol, why not apply for the official API prize? Dive into our tech, utilize it in a cool way and show us!

## Prizes
Stand to win up to $2000 SGD worth of KNC tokens for the themed bounty. Specific amounts can be found in the respective Github pages. The official API prize (Open Category) has a higher prize pool of $3000 SGD worth of KNC tokens!

## Judging Criteria
### 1. Idea
The importance of Kyber's protocol in the application, & originality of the idea.

### 2. User Experience
Intuitive, easy to use and interact with.

### 3. Technical Difficulty
Going above and beyond of what we specified. Good code quality, bug free, with thorough documentation.

### 4. Usability
Other projects are able to build on top of your application, or incorporate it into their own.

### 5. X Factor
Something that makes us go "Wow!"

---

## Contacting Us
We may have a booth set up during the hackathon, so drop by to meet us!
You may join our [developer group on Telegram!](https://t.me/kyberdeveloper)
