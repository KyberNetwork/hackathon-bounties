# Hackathon Bounties

We are excited to see what projects will come out of ETHDenver, the first ETH Global hackathon of the new decade!

<!-- Table Of Contents-->
[What is Kyber?](#what-is-kyber)<br>
[What has been built with Kyber?](#what-has-been-built-with-kyber)<br>
[Bounties](#bounties)<br>
[Prizes](#prizes)<br>
[Judging Criteria](#judging-criteria)<br>
[Contacting Us](#contacting-us)

## What is Kyber?

Kyber is a fully on-chain protocol that aggregates liquidity from multiple sources to power decentralized token swaps in applications like wallets, financial dapps, e-commerce sites and more! It can be used in 4 major ways.

### 1. End User Token Swaps
The simplest use-case that allows users to easily swap from any ERC20 token to another, including Ether. This functionality can be found in popular wallets like MyEtherWallet and imToken, and on websites such as KyberSwap and Easwap.

### 2. Trading Integrations
We allow for arbitrage bots to take advantage and profit off market inefficiencies, either by directly interacting with our smart contracts, or through our recently announced [trading API](https://blog.kyber.network/introducing-the-kyber-trading-api-b30550645b74).

### 3. Payments
Users can purchase virtual collectibles in the form of non-fungible tokens (NFTs) with any supported ERC20 token on Kyber. More broadly, any platform can widen their payment options from just Ether to include ERC20 tokens as well. Examples include Hodlmoon and Chainfuel.

### 4. Finance
A number of financial DApps use Kyber as an on-chain price feed. The liquidity provided by Kyber’s reserves are also used for index fund rebalancing, as one can see in Betoken and Melonport.


## What has been built with Kyber?

### Instant token swaps
Embed simple and atomic ERC20 <-> ERC20 token swaps in your application. [Enjin](https://blog.kyber.network/enjin-wallet-integrates-kyber-to-enable-in-wallet-token-swaps-476a08f9bf9a) and [KyberSwap](https://kyberswap.com/swap/eth-knc) are examples of these.

### Single Step Payments
Expand your payment options for your users by accepting not just ETH, but ERC20 tokens too. Empower your users with the freedom of choice in pay in their favourite tokens. [Hodlmoon](https://blog.kyber.network/hodlmoon-to-integrate-kybers-woocommerce-plugin-and-accept-token-payments-6baeda65c10e) and [Chainfuel](https://www.chainfuel.com/blog/chainfuel-integrates-kyberwidget-to-accept-erc20-tokens-for-telegram-community-management-automation) are but some examples.

### On-chain Fund Rebalancing
Achieve seamless liquidation of assets for immediate rebalancing of portfolios in a single transaction. Take a look at [bZx](https://medium.com/@b0xNet/kyber-bzx-b6f5330289a6) and [Betoken](https://medium.com/betoken/6-primordial-reasons-to-build-a-decentralized-hedge-fund-with-kyber-1bbb3ed6a4d9) for a glimpse of what is possible!

### Arbitrage Programs

Take advantage of market inefficiencies, since prices are not always the same across different price discovery venues, especially between off-chain and on-chain prices. Help improve price equilibrium across the market whilst profiting from it!

Here's the entire ecosystem map on what has been built on top of the Kyber protocol.

![Ecosystem Map](https://developer.kyber.network/uploads/kyber-ecosystem.png)


## Bounties

Here's what we're looking to be built in ETHDenver. We're offering a total prize pool of $5000 USD up for grabs!

### [Open Bounty](https://github.com/KyberNetwork/hackathon-bounties/issues/28)
Build a DApp that utilises Kyber natively for token swaps, payments, liquidity, or DeFi! The integration can be done via a smart contract, web3, RESTful APIs, or the KyberWidget.

Prize Pool: $500 USD x 3 teams

### [Profit & Loss Tracker for APRs](https://github.com/KyberNetwork/hackathon-bounties/issues/29)
Design and implement a fancy tracker UI for our Automated Price Reserves (APRs), showing the profit and loss margins since the start of their deployment. It should monitor the ETH and token balances of each reserve, calculate their current USD value, and compare it with the initial USD value of the initial amounts deposited.

Prize Pool: $1000 USD

### [APR Liquidity Metrics Dashboard & Simulator](https://github.com/KyberNetwork/hackathon-bounties/issues/30)
Our APR allows for different initial configurations. When onboarding new token listings, a FAQ we get is how prices adjust for a given amount of inventory and price range. Create a simulator that allows users to input initial parameters, and outputs statistics (Eg. slippage, price adjustments against inventory, etc.) and other relevant liquidity metrics of interest.

Prize pool: $1000 USD

### [Instant APR Factory Deployer](https://github.com/KyberNetwork/hackathon-bounties/issues/31)
Our current APR deployment requires multiple steps and contract deployments. Write a smart contract that minimizes the amount of steps required. For example, a user wishing to create an APR supporting an already listed token on Kyber can do so by just sending 2x the ETH inventory, together with the desired permission and liquidity param settings. The factory contract will automatically convert half the amount to the requested token and deploy the reserve and pricing contracts with the input settings from the user.

Prize pool: $1500 USD


## Judging Criteria
### 1. Idea
The importance of Kyber's protocol in the application, and originality of the idea.

### 2. User Experience
Intuitive, easy to use and interact with.

### 3. Technical Complexity
Going above and beyond of what we specified. Good code quality, bug free, with thorough documentation.

### 4. Polish
How refined your project is.

### 5. X Factor
Something that makes us go "Wow!"


## Terms and Conditions

The prize amount to be awarded to each team is at the judges’ discretion. Should the project fail to meet satisfactory levels, a partial reward may be given instead of the full amount. Additionally, being the only team that hacks for a particular bounty doesn't automatically make your team a winner. 

---

## Contacting Us
We may have a booth set up during the hackathon, so drop by and meet us!
Also, join our [developer group on Telegram!](https://t.me/kyberdeveloper)
