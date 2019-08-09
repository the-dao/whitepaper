# The DAO
## A next-generation decentralized organization that coordinates the resources of a community (human and capital) to sustainably deliver value for members.

**Authors**
DAO Community & Friends

**Table of Contents**
[TOC]

---

## Abstract

The DAO is a decentralized autonomous organization designed to sustainably develop a diversified portfolio of crypto-assets and accrue value for DAO members. It will be a clean capital pool where members only perform one vote to authorize a mandate that is executed by sub-DAOs known as “leagues” using the Aragon framework. During the life of a mandate, leagues perform all the standard work that an investment fund would require to be professionally managed over time, leveraging a decentralized global community where possible and allowing authorized, competent teams to self-organize and be appropriately remunerated when they deliver value. Leagues are able to distribute rewards based on coherent reputation-weighted peer-review using the SourceCred framework. Individuals can join the DAO at any time by buying DAO tokens, subject to a bonding curve to maintain incentive-alignment with risk profile. Members can exit the DAO at any time by selling DAO tokens via the same mechanism, thereby offering individual liquidity while ensuring security for members. The capital pool is managed through inflation and burning mechanisms: portfolio projects receive investment as newly-minted DAO tokens, and DAO tokenholders can always burn the DAO token against the bonding curve to obtain the underlying capital (ETH, WBTC, etc.) less a liquidity discount. This enables the DAO token to be a ‘stabler’ coin, collateralized by an underlying basket of high quality crypto-assets.

## Principles

As with any organization that is ['built to last'](http://www.wikisummaries.org/wiki/Built_to_Last), the DAO sets forth a set of inalienable principles that guides overall strategy along with the individual activities of members and related leagues.

### Clean distributed capital pool open to all

The DAO is clean capital pool. There have not been and will not be any discounts or preferential treatment to any party. There is no owner, no CEO, no point of centralization. On-boarding and off-boarding from the DAO along with remuneration structures of the leagues shall be transparent and in line with the Principles of the DAO. Leagues are subject to approval voting by all DAO token holders and can be changed if necessary at any time. Members can on-board and off-board at any time subject to security mechanisms and participation is pseudonymous and thus open to all.

### One interaction with DAO token holders per Mandate

Participation in the DAO should not be overly complicated for a passive member (DAO token holders). Given the history of difficulty in educating and motivating crypto-asset holders to participate in decentralized decision making, members should only need to make one decision per Mandate (a Mandate may be one year duration to start) which should be a single multiple-choice question to approve a single Mandate among a small set of 4-5 Proposals. Proposals by Leagues are whitelisted by a Compliance League and/or using Aragon Court for coherence as protection against attack vectors. Decentralization of proposal whitelisting will be introduced appropriately.
    
### Value creation

All members, whether providing services via a League, allocating capital, whether vetted or open community members, are incentivized towards the pursuit of value accrual to the DAO portfolio. Using continuous payments to individuals who work full-time for Leagues, providing compelling bounties and rewards for community members that deliver value, the DAO’s bullet inflation mechanism will reward Leagues and members that deliver outlier value as investments and value-add activities are harvested by the DAO. The DAO's primary edge is its ability to scale the value-add contribution that a top-tier venture fund should deliver to its portfolio of projects. The DAO will be the highest value-add partner to its portfolio of projects because it will be able to deliver the true scarce resources of the crypto industry: developers, active, engaged community, beta testers, a privileged knowledgebase and global scale through its distributed network of members.

### Ensuring security

In delivering security to members, we note the need for resilience and certain stability mechanisms in the capital pool must exist. Compliance can be achieved as a decentralized service performed by the Leagues on behalf of a clean capital pool. Such an arrangement present interesting game-theoretic challenges. We propose certain solutions below and in subsequent League specifications.

## Current issues in capital deployment

### Issues with legacy fund structures

While many venture capital funds (VCs) are well-intentioned and do great work for their portfolio, there remain inherent structural limitations of the standard VC model:

1. **Scaling value-add** Many investment funds start out being committed to "value-add", i.e., they deploy time and capital in assisting their portfolio projects alongside the initial capital invested in the project. Early-stage venture capital firms will help with recruiting, crypto-economic design, community management and other services. However, as a fund scales it is difficult to scale the value-add model along with AUM (assets under management) unless the fund commits to linearly scaling the team. 

2. **Fair compensation for value created** Start-up economics are especially skewed to favour the founder(s) who were present at inception, even though subsequent employees may generate substantial value. Actual value creation vs. value capture is frequently skewed in favour of early capital contributors and founders. Changing this dynamic to make an organization more attractive for top-tier talent to enter post-inception could create a vortex for high-value contributors who can be confident that they will share in the value they create accordingly and desire to be treated like an owner. 

3. **Geographic reach** VCs, especially in crypto, often are regionally strong but don't have a global footprint. However, most of the major projects in Ethereum and generally across crypto have global ambitions. Thus crypto communities require an understanding of diverse, idiosyncratic markets. An investor-partner that has a truly global footprint and is able to help portfolio projects in a range of different geographies can create more value for companies and investors than traditional VCs.

4. **Liquidity** Two predominant capital pooling/allocation structures exist, each with liquidity trade-offs: evergreen hedge funds and close-ended venture funds. In the hedge fund model investors have liquidity on a few months' notice. This affects a fund operator’s incentives and decisions: liquidity of underlying holdings must be maintained, and managers are often compensated on an annual basis, creating focus around the given calendar year, sacrificing long-term value creation in order to harvest short-term profits. A venture fund structure with a lock-in period of 7-10 years can be a difficult purchase decision for investors because the asset is illiquid for a long period of time. Further, there isn’t any mechanism for investors to onboard after an initial period, thereby closing off venture returns to an exclusive group. There should be a mechanism whereby investors can on-board after the initial capital formation and off-board reasonably should they require liquidity. Investors that on-board late should naturally pay a premium for doing so and investors that off-board early should bear some reasonable liquidity penalty.

5. **Social scalability** Most funds have a few key individuals (known as "key persons") that drive the vast majority of deal flow. However, a fund could benefit from a community or network of motivated members that drive substantially more deal-flow and contribute value-add activities to portfolio projects. A filtered community incentivized to find, assess, and support projects could increase the quality of deal flow and the reputation of the organization. Experimentation with novel social coordination tools such as [SourceCred](https://sourcecred.io/) can ensure incentives among a coherent community and thoughtful debate while ensuring information security when appropriate.

### DAOs

The DAO (April to July 2016) was a novel experiment in capital formation and distributed decision making in the allocation of the underlying capital. A community pooled capital by buying DAO tokens and used governance to deploy capital in a for-profit motive, thereby driving the value of the underlying capital pool. In retrospect, the early days of the DAO proved quite interesting as an enthusiastic decentralized community self-organized and performed due diligence on potential deals. Unfortunately, The DAO had a critical vulnerability in its redemption mechanism, which was exploited and the project failed. However, if the DAO had not failed, it would possibly be the largest capital pool in the industry today. Further, the due diligence standards and requirements that The DAO members were establishing would have made for a much more tempered and coherent subsequent era of funding protocols than what we saw in the ICO craze circa 2017.

## 2. DAO Structure

![](https://i.imgur.com/MhYNmaW.png)

The DAO is a decentralized software stack based on the [Aragon framework](https://aragon.org) that allows capital to be securely pooled and intelligently deployed to fund crypto-networks, dapp projects, companies and trading opportunities. The underlying pool of capital will be a balanced portfolio of whitelisted assets such as ETH, WBTC, and other high-quality crypto-assets. The pool is to be safeguarded and managed efficiently by leagues working under strict time-limited mandates with security backstops regarding performance.

Note: While trustless cross-chain value transfer has not yet matured, over time, members would expect that the DAO will also hold off-chain assets and crypto-assets that are not native to Ethereum, potentially via service from a bonded custody league.

At the genesis of the DAO, capital can be onboarded during an initial funding period. After the close of initial funding, entry into and redemption from the DAO will occur against a bonding curve that regulates the pricing of the DAO token in units of the underlying capital. 

The DAO will make capital deployments based on a set of permissions set in a multi-sig between the Venture League, Treasury League and Compliance League, subject to the permissions set forth in the respective mandates for each group. For capital to be sent by the DAO to a prospective investment, the Venture League, Treasury League and Compliance League will all need to sign a multi-sig transaction and the given deployment will need to satisfy the permissions and restrictions of the issued mandates to each league.

### DAO Specification

The DAO consist of a series of League-DAOs using a specific hierarchy of permissions within the Aragon framework. These DAOs are organized through assigning roles and permissions in relation to one another. We categorize the whole system as a DAO, where the highest-level DAO is called the **Parent** and the rest are called **Leagues**, which are technically DAOs in their own right subject to nested permissions. In principle the parent DAO will push any and all activities during the mandates down to the league level. Each DAO will require its own design process and specification, but we offer a brief illustrative overview below.

### Parent_DAO

Ultimately responsible for the funds of DAO members, and where all governing members vote on mandate selection. Voting is limited in the Parent_DAO to once per mandate (subject to the Benny Switch below); Day-to-day maintenance is delegated to the underlying League DAOs – Venture League, Treasury League, Compliance League, Dev League and so on, based on the permissions in their given mandates. This is similar to the way a board of directors have control over the leadership in a company, but the day-to-day operations are managed by functional departments. The Parent_DAO does not have direct access to spending its own funds rather that functionality is managed through the multi-sig between the Treasury League, Venture League and Compliance League.

### Spend_Funds

A multi-sig that has the authority to execute Token transfers of the DAO tokens via inflation of the DAO token. The only members are the Treasury League, Venture League and the Compliance League. The Treasury League is allowed to make a vote to mint tokens and transfer them while the Compliance League is will simply ensure the values are correct, but has no ability to cast a vote. 3/3 of votes are required to transfer funds. Every payment should have a time delay before execution (example 14 days) to allow for an appeals process within the Venture League.

### Treasury_League

Responsible for managing the underlying capital of The DAO, specifically rebalancing the portfolio of underlying capital and executing inflation-based payments. This would be a bonded league (i.e. posts a collateralized position vs the current mandate’s capital) that would have specific permissions concerning the maintenance of portfolio balance, co-signing for capital deployments in deals proposed by the Venture League, and other management of liquid tokens such as 3rd party custody of certain assets. 

### Venture_League

The Venture League would be the team that is responsible for sourcing deal flow and finding compelling investments. This League could be well suited for open community involvement in some way using appropriate social coordination tools. Obviously, with a proclivity for a structure that ensures confidentiality of certain deals (see Community below).

### Compliance_League

Responsible for ensuring Spend_Fund votes are accurate, the Venture League and Treasury_League are within their expected permissions and the capital deployment in question is in line with the principles of DAO. Compliance_League will also be responsible for white listing mandate proposals together with Aragon Court after the original mandate. This would be the third signature in the multi-sig to deploy capital during the mandate. 

***Note on Compliance***: Questions are naturally raised about the compliance of the DAO and potential classification of the token as a security by the SEC in the USA. We note that making a provision for a team to work with regulators towards agreeable solutions is a substantially more significant effort at compliance than what the industry has seen from DAOs before. Given that the DAO token is merely a basket of tokens that are already not considered securities, both the launch of the DAO network and token issuance are a) executed with sufficient level of decentralization as according to the [SEC](https://www.sec.gov/news/speech/speech-hinman-061418), b) not a common enterprise or expectation of profits from the work of others because the leagues don't yet exist nor are formed, c) the inflation mechanism amounts to a payment token under Swiss FINMA regulation. At the time of conceptualizing the DAO, most of the authors of this specification are optimistic that work can be done by a well-intentioned competent Compliance League to achieve reasonable compliance without sacrificing the principles above, namely that the DAO remains a 'clean capital' pool that participants can freely enter into and leave from reasonably without discrimination. 

### Dev_League

This league would be responsible for due diligence of potential acquisitions, development of software for coordinating between the leagues and value-add services for portfolio projects in which the Dev_League would be naturally remunerated for.

### Oracle_League

Initially, an Oracle will be required by the DAO for relevant price feeds and striking NAV, especially considering future illiquid assets. This oracle would also be bonded and there is a range of decentralized oracle providers now available such as [Chainlink](https://chain.link) that could potentially provide this service today with minimal integration available to Aragon DAOs.

### Original_Guild

During the first mandate the Original_Guild (OG) operates like a proxy using Aragon Court. The OG has pseudo-privileges over other Leagues, meaning they should be able to freeze a DAO to prevent any rogue behaviour. These activities can be executed by the Aragon Court while ensuring appropriately decentralization in the launch and execution of the DAO. The Parent_DAO has similar privileges over the OG so that the Parent_DAO can freeze the OG_DAO in the case of rogue behaviour. After the original mandate, the OG will be dissolved and white listing future mandate proposals will be executed by Aragon Court in concert with the Compliance League.

## Mandates & Proposals

A mandate is; 
1. A set of permissions for execution of specified activities; 
3. Using a specific set of resources; 
4. Over a specifically defined period of time; 
5. Which aims to create a specific outcome.

For example, a mandate could be to deploy 5% of DAO's capital (via inflation) over the course of 1 year and the Leagues will split a service payment of ~2% of total AUM plus 20% of the profit generated from the investments made during the given mandate, when they are harvested. So a $25 million capital pool would then generate fixed fees of 500k, which is enough to cover salaries for some teams operating leagues along with some financial incentives for community participants, with considerable potential upside if the given mandate produces compelling investments that results in outlier returns. Once a mandate is approved, the portion of capital allotted is added to the illiquid assets for the purposes of the liquidity provisions.

### Proposals
Proposals are an offer by one or more leagues to perform a mandate, with specific deliverables, permissions, timeline and outcome. Proposals can be made by any League or group of Leagues acting in concert. During the proposal era, anyone can make a Proposal for a mandate. However, only a whitelisted set of 4-5 potential mandates will actually be voted on by DAO members. 

### Whitelisting Proposals
Any group can conceivably self-organize into a league and make a proposal to the DAO to perform a mandate. A league or group of leagues that propose a mandate also must also be able to full the requirements to execute their proposal. For the first mandate decision, the Original Guild will be formed using Aragon Court to perform the white-listing of proposals shrinking down the number of proposals to a reasonable multiple-choice question.

### Benny Switch
A Benny Switch, named after [Benedict Arnold](https://en.wikipedia.org/wiki/Benedict_Arnold), is a way for DAO members to remove the permissions of a malicious league or group of leagues under emergency conditions or an attack. The Benny Switch engages if a minimum quorum of DAO members signal with their tokens that a Benny Switch vote is necessary. Then a subsequent vote occurs whereby a minimum quorum votes in favour of either removing a specific league's permissions or ending the entire mandate immediately. Given the issues with achieving minimum quorum in related crypto-networks with on-chain governance in the past, we would propose ~~dynamic quorum~~ adaptive quorum biasing whereby the minimum quorum necessary changes based on voter turnout.

## 3. Capital Formation - Bonding Curve

![](https://i.imgur.com/O4qSxnc.png)
*Bonding Curve Plotted on Cartesian Coordinates, including the time step function.

For any capital pool to deploy resources intelligently and deliver on a value-add portfolio, it requires sufficient assets under management AUM to cover the cost of operations and management. However, too much capital for the sizing of the market of target investments can also be an issue. As with any investment, the initial entrants into this reserve assume more risk than later entrants as the probability of success clarifies over time, especially with novel models such the one described herein. Early entrants should be rewarded for this asymmetric risk profile in support the DAO. Thus, we propose an initial capital formation period whereby early contributors receive a bonus of DAO tokens vs. subsequent contributors. The cumulative bonus should reflect the liquidity discount for off-boarding during the initial bonding curve period.

DAO requires a mechanism that allows for DAO members to off-board reasonably if they require liquidity and potential new entrants to buy-into the DAO membership even after the original capital formation period in order to become incentive-aligned. Thusly we propose a bonding curve whereby one can buy into the DAO with ETH, WBTC or another approved ERC20, known as “Underlying Capital” in exchange for DAO tokens in an increasing-cost bonding curve function. Conversely, a DAO member can burn DAO tokens and obtain the underlying liquid tokens less a liquidity penalty that is correspondent to the illiquid positions in the DAO plus the capital earmarked in the current mandate.

A bonding curve controls the inflation of the token supply in a way that fulfills both of these requirements.

![](https://i.imgur.com/22oRU0f.png =250x) [Note: Float left to the Equations ]
*Graph plotted on the proper Polar Coordinates*

- $r\ = ac^{\theta}$
- $a\ =$ Bonding Curve Starting Price
- $c\ = \phi^{\frac{1}{90}}$ = 1.0053611
- $\phi =$ Golden Ratio = $\frac{1+\sqrt{5}}{2}$ or 1.6180339887
- $\theta \ = (TokenSupply-StartingSupply)*TokenRatio$
- $TokenRatio = \frac{90}{Starting Supply * 4}$ 
    - Required tokens to rotate 90 Degrees on the Polar Graph

### Phase 1 - Incentivise early on-boarding of capital

The initial funding period will allow for a bonus of DAO tokens to be minted in exchange for Underlying Capital (ETH, WBTC, etc.). This bonus period will decrease as a step function during an initial funding period of 3 months thereby incentivizing early deployment. 

The minting price of the token will increase at each interval after reaching a specified block height.

![](https://i.imgur.com/eM29r2q.png)

Initial Step Prices
| Time ≈  | Block Height | Token Price |
|---------|--------------| ------ |
| 0 Weeks | 0      | $50 |
| 2 Weeks | 89000  | $65 |
| 4 Weeks | 178000 | $77 |
| 6 Weeks | 267000 | $85 |
| 3 Months| 534000 | $89 |

At the launch of the curve $a =$ $89.00, the Final Token Price.

The onboarding-phase is a long enough period to allow for awareness to build widespread global participation, and short enough to add value to early participants.

#### Security
Due to the nature of mandate selection, if a single holder owns a majority of tokens, they can theoretically decide single-handedly the recipient of a mandate and act maliciously. Including a function whereby the cost of acquisition increases geometrically offers sufficient protection of attack from a well-capitalized malicious actor and thus the bonding curve is necessary to control both a run on the underlying capital in a market downturn as well as an attack from a well capitalized actor. If the community sells their tokens, this is a form of consent whereby the individual gives up their right to vote in mandate selection. It should just become gradually prohibitive to attack the DAO through DAO token minting.

For a takeover attack through minting, because participation is not restrictive at the level of identity, it is not possible to outright prevent the case where an individual takes majority control of the token supply. However, capital is Sybil resistant if directed through a bonding curve.

## Off-Boarding

After the initial funding period, DAO members can off-board via the bonding curve with a predefined penalty that corresponds to the illiquid position of DAO plus the capital contemplated in the current mandate. For example, if the DAO holds 5% of its AUM in illiquid assets and the current mandate is to deploy 5% of the AUM, the illiquidity penalty would be 10% in addition to falling on a bonding curve and increasing as more and more DAO tokens are subsequently burned over a given short period of time.

### Last Man Standing
Inherent to the design of DAO is a principle of favouring the Last Man Standing. Redeeming parties effectively leave their private allocation plus the current mandate as a penalty, thereby leaving the remaining DAO members with an accreditive position containing a larger share of the private assets. If the Venture League does its job correctly over time, those assets should be the most profitable assets over the long run. Thusly the on-boarding and off-boarding structure favours first-in-last-out DAO members. If a member maintains their position through all the ups and downs and liquidity crunches in crypto, that member should stand to be rewarded by the best-performing position.

### Burning/Redeeming Tokens
$BurnPrice = CurrentMintingPrice * LiquidityRatio$

$LiquidityRatio = \frac{LiquidAssets}{Liquid + Illiquid}$

The treasury provides the liquidity ratio through an oracle. Thusly, the burn function is not activated until a mandate has been selected, and there exists an entity to fulfill this role.

#### Example
One can imagine a scenario where the treasury holds 100 Million and 10%, or 10 million, is held in illiquid assets. At this moment the Burn Price is 90% of the NaV. If one sells to the curve, one receives 90% of their share of the NaV. After all, a token represents fractional ownership of all of the underlying assets. The rest is burned in the purest sense, and the remaining token holders now own a higher proportion of the illiquid assets than previous. i.e., the same token represents more illiquid assets than before.

If individuals continue to sell, liquid assets are exchanged to provide liquidity for redemptions. This, in turn, increases the Liquidity Discount as the inverse of the Liquidity Ratio.

![](https://i.imgur.com/fB74NMo.png)
 
## Community
Central to the value proposition of Venture League is leveraging the community for both sourcing deal flow and vetting potential deals. Leveraging novel social tools that allow teams to maintain a certain level of confidentiality when putting together a specific deal, but then also allow for community feedback and proposal of new opportunities.

One solution could be a tiered structure where the ultimate investment ultimate responsibility for decision making is held by a small core team, but community members are rewarded for providing information, leads and work on behalf of all token holders. This reward can be for direct value-add to the portfolio companies or through vetting potential investments increasing the surface area of deal flow available to the core team, using SourceCred for reputation-weighted peer review.

![](https://i.imgur.com/y0qj4BA.png)

## SourceCred - https://sourcecred.io/

Past a group of 5-7 (known as a “two pizza” team) it can be difficult to coordinate and evaluate individual contributions, especially in teams that are distributed globally.[SourceCred](https://sourcecred.io) provides a toolbox to have reputation-weighted peer review of distributed teams and communities. SourceCred runs a modified version of PageRank on a contribution graph to produce a cred attribution. The weights within the system are highly configurable to match the needs of the community and one would expect that each League will organize its SourceCred algorithms accordingly depending on the parameters of that working group and the nature of their mandate.

Through the use of SourceCred individual members of the community can earn reputation, as defined by the community and specifically community leaders, and be compensated for the value they bring into the system. Over time this lowers the barrier of entry into the community and encourages high quality work fulfilling the mission of the DAO. Most importantly, this fosters a culture whereby leagues and the individuals who comprise them have an understanding that if they deliver great value, they will be adequately compensated for their contributions. 

## DAO Token
DAO tokens will be issued to leagues for services, projects as medium of investment and members in exchange for Underlying Capital. They confer governance rights to decide mandates and ultimately guide the direction of DAO and can be used for staking in the Aragon Court assembly of the Original Guild as well as staking for conflict resolution. The DAO token is issued when a deployment is confirmed by the multi-sig between Venture League, Treasury League and Compliance League and the DAO token is considered a basket of the underlying assets of the capital pool via bullet inflation. That is that the Treasury_DAO can inflate DAO tokens subject to the permissions of the given mandate and thusly balance the portfolio.

### Stabler Coin
The DAO token will be redeemable for the underlying liquid assets that it represents. For example, if the underlying capital pool is 1/3 ETH, 1/3 WBTC and 1/3 a basket of other tokens without any private assets held, then the DAO token can be burned in exchange for those assets less a small liquidity penalty corresponding to the size of the current mandate. This makes the DAO token a basket crypto-currency which should allow it to be somewhat stabler than any of the individual crypto-assets in underlying capital while still being a long-crypto asset. Such a mechanism sometimes known as a 'Stabler Coin'. Potentially, a [SET](https://www.setprotocol.com) could be deployed in support of this corporate currency backed by a basket of cryptocurrencies.

---

## Conclusions
Herein we present a framework and set of incentivization mechanisms to drive value creation among decentralized P2P actors in a for-profit capital pool. It is understood that there are numerous crypto economic and security mechanisms to elaborate and evolve before deploying this set of smart contracts. However, we find the dream of a sustainable decentralized organization that attracts and filters for great talent, supports genuine innovation and meaningful experimentation, and delivers outlier value to its members to be so prescient that we are compelled to forge ahead with development and eventual deployment because this is the most interesting project we can imagine to be a member of.
