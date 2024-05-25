# Niti: Non-custodial Interlinked Tokenization Infrastructure
## Draft Version 0.1.0
## Caleb Isaac

## Hyper-colateralizated syntectic assets on Bitcoin through Lombard Credit via Discreet Log Contracts

### 1. Issue

Bitcoin is often pointed as a strong candidate to become the world-wide reserve currency. However, though it has become one of the main assets used as store of value, it is not yet adopted worldwide as a mean of exchange. The explanation to this fenomenon can be split in two aspects:

#### 1.1 Currency paradox (Saving Paradox)

Derived from Gresham's Law, comes the "Currency Paradox":

"_Ceteris Paribus_, rational agents prefer spend currencies with low potential as store of value, while they tend to accumulate currencies with greater potential as a store of value for future exchanges."

For example, if an rational agent receives half of it's salary in dollars, and the other half in venezuelan bolívars, your rational atitude is to spend first the venezuelan bolívars and reserve the dollars for future exchanges, once this one can, relatively, keep its value better through time.

Bitcoin, being the less inflationary currency existent and with greater potential as store of value through time, tends to be accumulated, and not spend, reducing its using as a mean of exchange.

#### 1.3 Layered Money

The direct using of Bitcoin as a store of value and mean of exchange violates the concept of Layered Money, elaborated extensively on the Allan Schramm's article "Bitcoin, the system of final settlement." and the book "Layered Money" from Nik Bhatia. Gold wasn't used extensivelly as a mean of exchange, but through layers that made it usefull as a mean of exchange.

Observing the evolution of the using of gold as the basis of the monetary system, it's possible to divide it in four layers: the first being the metal itself after extraction, gold nuggets in their original form. The second layer is the standardization of this material into gold bars that follow high standards of purity, shape, measurement and weight. The third is gold certificates, where these bars, difficult to transport and divide, were "tokenized". The fourth layer is the banknotes as they were known before the end of the gold standard, backed by these certificates that circulate en masse.

Each of these layers have distinct attributes and focuses to perform their respective functions. The notion that Bitcoin in it's raw form would maximize all the needed caracteristics of a monetary system (store of value, mean of exchange and unit of account) does not allign with the history of money in humanity.

If we wish Bitcoin to be used as a mean of exchange, we need to recognize this currency paradox and the concept of layered money so we can create a Bitcoin-based monetary system that supplies the market demands.

#### 2 Current sollutions

#### 2.1 Centralized Stablecoins (IOU)

The IOU Stablecoins are assets in which it's value derives from being backed by Fiat reserves or other traditional assets kept by a centralized entity. Examples includes Tether (USDT), USD Coin (USDC) and DePix. Those stablecoins are essentially tokenized promisory notes issued by private companies, i.e., they carry a significant counterpart risk as you lose custody of your bitcoins, and you need to trust the company that issues them that they keep honestly complete reserves, and that will redeem tokens as promised.

Previous cases of lack of transparency and imcomplete audits eroded the trust with scams and bad using of the colateral, resulting in the loss of parity of the token. In addition, those centralized stablecoins are suceptible to governamental regulations and can be censured or closed at any time.

Despite of the mentioned issues, they are extensivelly used: Theter (USDT) is the third greatest criptocurrency, and is heavilly used as a mean of exchange in third world countries as a tokenized dollar.

#### 2.2 Algorithmic Stablecoins

Contrasting with the IOU Stablecoins, which reintroduce the centralized counterpart risk, Algorithmic Stablecoins doesn't have a centralized issuer or Fiat reserves. They are backed by a digital asset, and the conversion is performed by smart contracts. Some examples are the USD of 10101, MakerDAO and TerraUSD.

Although they have clear advantages over IOU Stablecoins, they have a giant additional cost: hypercolateralization. All of them require a greater backing collateral than the equivalent value of the fiat stablecoin issued. In addition, the user must have tecnical knowledge of the specific algorithm used to keep that parity, which is different for each currency, and also knowledge of the digital asset used as collateral.

In this way, to the avegare user, the risk perception is high, as these ventures do not follow a standard protocol with a standard asset as reserve. In the case of TerraUSD, the risk was so high that it collapsed: the collateral used were weak assets in which it's value was linked to the protocol itself. For this user, using a centralized and legal solution is safer than an unknown one to him, even with a supposedly safer mechanism. 

The the average user, this cost is greater than the benefits of using a centralized stablecoin, which has a cost of 1:1, instead of a cost of, let's say, 2:1 required to generate the hypercollateralization of algorithmic stablecoins. The average user prefers to take the temporary risk of Tether not succumbing rather than spending capital to create the collateral. The entire focus of these protocols is to create fiat currencies and compete directly with IOUs, using their own mechanisms, which we believe is not a viable market strategy.

NITI has a different strategy: create a universal protocol for creating stablecoins by the users themselves, focused in assets that centralized stablecoins cannot create.

#### 2.3 NITI's Proposal

NITI proposes to implement the monetary system that Hayek has proposed in 1976, in the book "The Denationalization of Money", creating a platform where various stablecoins can compete freely, following all the same protocol to ensure it's quality.

#### 2.3.1 Hayek's Monetary Model and NITI's Implementation

In his book "The Denationalization of Money", published in 1976, the economist Friedrich Hayek proposed a new monetary system. He argued that the State Monopoly over currency issuance is the root of many problems, such as inflation, boom and bust cycles, and monetary crisis. Hayek stated that the final solution is to allow free competition on issuing private currencies.

In this model, private institutions can now emit it's own currencies, which can now freely circulate on the market. The users would choose the currencies they consider more stable and trustful. Currencies that did not maintain their value would lose public confidence and be abandoned in favor of better alternatives.

According to Hayek, this monetary competition system would take to more stable currencies and adjusted to the market demands. Issuing institutions would have strong incentives to keep the value of it's currencies, 'cause their reputation and business would depend on that. They would seek to meet user's demands for currencies with different characteristics, such as greater or less stability, backing in different assets, etc.

NITI proposes to implement this Hayek model using Discreet Log Contracts technology on Bitcoin (DLC's). Through DLC's, any person or institution can create a Algorithimic Stablecoin (called "Synthetic assets" in NITI's terminology) backed by a variety of assets, way beyond what traditional stablecoins backed by fiat currencies can offer.

This synthetic assets could have their value linked to commodities, stocks, indexes, fees or any other asset with a public and verifiable price. Each emitter could now choose the basket of assets to use as collateral on your synthetic asset, seeking to serve specific market niches. The users can, for instance, choose the synthetic assets that fullfils better it's personal needs of stability, hedge, exposure to specific sectors, etc.

Differently of current algorithmic stablecoins, that has each one it's own complex and risky mechanisms of stabilization, all NITI's synthetic assets will follow the same pattern model using DLC's. It will bring transparency, security and usability to users. They will know that all synthetic asset, independently of who is the issuer, follow the same operating logic.

Therefore, NITI seeks to create the technological basis to make viable the monetary competition model proposed by Hayek. It will be a huge step towards the Denationalization of Money as glimpsed by Hayek decades ago.

#### 2.3.2 Token diversity

Instead of directly competing with IOU's, our proposal is to implement something that they're unable to do by it's own nature: token diversity. Tether has direct reserves for its backing and this is possible because of the high liquidity on the traditional market of dollars, future contracts, treasure bills, etc. Meanwhile, if they wanted to create a token that emulates the Diesel price, which would be very useful to truck drivers to have a hedge agains its own costs, they would find it very difficult. They can try to use fuel stocks as backing, but it has high costs and it would make unfeasable the monetization of this reserves. It may be even possible to create a dynamic basket of traditional assets to emulate this price, but it is possible to see how this system would rapdly increase in complexity and reduce its profitability.

In the case of creating a stablecoin that is pegged to the variarion in the transaction fee rate (sats/vB) on Bitcoin, there are no legal instruments in the traditional financial market to create, or monetize this reserves. This type of stablecoin can't be created through IOU's, and we believe that it is in this type of asset that algorithmic stablecoins have a competitive advantage.

Niti's synthetic assets can be pegged to climate variations, harvest volume, political events, transaction fees on Bitcoin, price averages (E. G.: mean price of Bitcoin in the last 200 weeks), stock indexes and any other assets with public data and trustable information sources and which the two parties of the contract rely on. Diferently of the IOU stablecoins, its system do not rely on direct backing, but only a private contract between two parties which uses bitcoin as collateral, allowing specfic synthetic assets to be created for specific and peculiar cases. Niti found this gap in the market, as although algorithimic stablecoins have the technical ability to generate tokens of anything that has public prices, they focus on copying fiat currencies and competing with IOU stablecoins.

#### 2.3.3 Standardization

Algorithmic stablecoins present high complexity to users as they follow their individual protocols, which can be flawed, as was the case with TerraUSD. The user then needs to specifically study that process in depth to undestand these risks and economically analize the viability of the parity of the offered tokens. This is unfeasible to the average user, who in practice takes a high risk when participating in a system that he doesn't know and is unique to that protocol.

In the solution proposed by Hayek, distinct private currencies would compete freely on the private market. He argues that our view of using a single currency based on the custom of the state monopoly, and we should use various synthetic assets (stablecoins with no direct backing), based on various asset baskets to the distinc uses of money. Niti has the objective of bringing this system to life, with over 50 years after its conception. So, Niti is not a bank offering stablecoins, but it is actually a protocol where market agents can use it to create their own stablecoins, that necessarily need to adhere to the protocol model

This way, using companies that follow Niti protocol to create these stablecoins, the customer know he is using a safe platform, indenpendently of which token he is buying. With the standardization of algorithmic stablecoins, the complexity and the risk perception is highly reduced to the customer. TerraUSD would never operate on Niti, because its system could not follow the standard protocol accepted and known by everyone. Niti uses the Blue Ocean Strategy a new value proposal not yet used by any algorithmic stablecoin.

#### 2.3.4 Niti's Blue Ocean Strategy

According to KIM and MALBORGNE (2008), strategies such as Blue Ocean seek to create uncontested market spaces, as oposing to competition in an existing space. Focuses on making the competition irrelevant, and doesn't necessarilly care about beating it, because the company that uses the Blue Ocean Strategy compete for different customers, in a wider market, with different value proposals of what is offered on the market. The tools used on this research consists on the Matrix of Value Evaluation, which serves as a basis for diagnosing the company as a model for developing a new strategy; the Model of the four actions, used to question the business model used by competitors and propose changes on the company value curve; and the Matrix of eliminating-reduce-elevate-create, a complementar model to the four actions model and comunicate the needed actions to achieve the new value curve proposed by the strategy.