#### This document aims to collect resources relevant to Ethereum's current issuance discussion.

*This page is maintained and kept ~up-to-date\~ by [Caspar](https://twitter.com/casparschwa). Feel free to ping with questions/comments/requests on Twitter or Telegram @casparschwa, and please point out missing resources.*

## Introduction

Ethereum's issuance policy is effective at ensuring a minimum level of staking and thereby economically guaranteeing reasonable security.

However, the current issuance policy has effectively no control over the upper limit of stake participation. A too high staking ratio, ${staked\ ETH}\over{total\ ETH}$, comes with downsides that need to be considered carefully.

For this reason, proposals to change Ethereum's issuance policy were put forward and are currently discussed.

The goal of this document is to collect all resources (writeups/talks/podcasts/etc.) relevant to Ethereum's *current* issuance discussion.

## Highlights
*Disclaimer: This section is <u>**subjective**</u>. Please take a look at the following section for a more exhaustive and unopinionated list of resources.*

For an overview on the current issuance debate, the following resources are a good starting point; in \~rough\~ order of suggested consumption:

#### Technical highlights ($\geq$ 🤯🤯)
1. Ansgar&Caspar's [issuance endgame(tm) post](https://ethresear.ch/t/endgame-staking-economics-a-case-for-targeting/18751) explores why Ethereum is plausibly heading towards a very high % stake evnvironment under its current issuance policy; it then argues for why this future is problematic, and suggests to *target* a low staking ratio in the issuance endgame. 
2. Caspar's talk [issued issues](https://t.co/nc8NHaPj4b) focuses on *why* to change the issuance policy, i.e. the problems of a high % staked environment.
3. Anders' [master piece](https://ethresear.ch/t/properties-of-issuance-level-consensus-incentives-and-variability-across-potential-reward-curves/18448/) proposes and analyzes new reward curve(s) with tempered issuance. Beyond the specific curve(s), it is a valuable resource to learn about relevant properties when considering issuance curves. Note that in broad strokes, Anders considers this proposed issuance policy to be viable for the endgame, while Ansgar&Caspar consider it a great *short term* issuance policy before moving to a stake ratio targeting policy for the endgame. 
4. Mike's [2$^{nd}$ Issuance Issues](https://notes.ethereum.org/@mikeneuder/subsol) takes the time it deserves to provide more intuition for a key point of the issuance endgame(tm) post: why *real* issuance yield can be higher in the long term equilibrium, despite a reduced (!) issuance policy.
5. Anders' deep-dive on his [thinking about the trade-offs](https://ethresear.ch/t/faq-ethereum-issuance-reduction/19675) when exploring various potential issuance policies in an FAQ format. Note that his views differ to Ansgar&Caspar's on <u>*some*</u> aspects, e.g. desirable staking ratio target or viability of non-targeting policies for the endgame. 
6. If you prefer podcast format, this [Uncommon Core episode](https://open.spotify.com/episode/2YhHNjUwj44F1C3LXcCP0N?si=YmbgzZwcRTqaYVct6AzkfA) (also on [YouTube](https://www.youtube.com/watch?v=ivynR3RI3_Y)) is your 2.5h one-stop solution. It outlines most of Ansgar&Caspar's thinking behind the issuance endgame(tm) post + productive debate with Hasu&Jon.

#### High-level highlights ($=$ 🤯)
1. Caspar's talk [issued issues](https://t.co/nc8NHaPj4b) focuses on *why* to change the issuance policy, i.e. problems of high % staked environments. 
2. Mike's [Initial Issue](https://notes.ethereum.org/@mikeneuder/iiii) is a more high-level take on the endgame post(tm) and presents his view on the matter.
3. In this [Bankless episode](https://www.youtube.com/watch?v=GLP_qRyPuv4) David & Ryan "give a masterclass on monetary policy for Ethereum and beyond".
4. In this [Epicenter episode](https://www.youtube.com/watch?v=2krlPcbpZvQ) nixo & superphiz from EthStaker talk about the issuance debate with a focus on the solo staker perspective.

## Exhaustive list of resources
### Writings

#### *by [Ansgar](https://twitter.com/adietrichs) & [Caspar](https://twitter.com/casparschwa)*

|Title|Description|🤯?|
|-----|-----------|----------|
|[Endgame Staking Economics: A case for targeting](https://ethresear.ch/t/endgame-staking-economics-a-case-for-targeting/18751)|Explores the past, current and probable future of staking levels, what negative externalities of too much stake are, and argues for why targeting a low % of stake is desirable as the endgame issuance policy.|🤯&#160;🤯|
|[Electra: Issuance Curve Adjustment Proposal](https://ethereum-magicians.org/t/electra-issuance-curve-adjustment-proposal/18825)|Short-term proposal to lower issuance curve from cF√D to cF√D(1+kD) as proposed and analyzed by Anders.|🤯&#160;🤯|

#### *by [Anders](https://twitter.com/weboftrees)*
|Title|Description|🤯?|
|-----|-----------|----------|
|[Minimum Viable Issuance](https://notes.ethereum.org/@anderselowsson/MinimumViableIssuance)|Long thread arguing for minimum viable issuance to be an important pledge to the regular Ethereum user.|🤯&#160;🤯|
|[Properties of issuance level: consensus incentives and variability across potential reward curves](https://ethresear.ch/t/properties-of-issuance-level-consensus-incentives-and-variability-across-potential-reward-curves/18448/)|Analyzes the effect of issuance level on consensus incentives and reward variability across potential reward curves. Recommends decreasing issuance at high staking levels, by changing the issuance curve from cF√D to cF√D(1+kD).|🤯&#160;🤯&#160;🤯|
|[Reward curve with tempered issuance: EIP research post](https://ethresear.ch/t/reward-curve-with-tempered-issuance-eip-research-post/19171)|Aims to present the rationale for a reward curve with tempered issuance, i.e. cF√D(1+kD).|🤯&#160;🤯&#160;🤯|
|[Foundations of minimum viable issuance](https://notes.ethereum.org/@anderselowsson/Foundations-of-MVI)|Takes a closer look at the dynamics of cost and surplus in staking, demonstrating how all token holders can benefit from reduced issuance.|🤯|
|[Reward curve with capped issuance](https://notes.ethereum.org/@anderselowsson/Reward-curve-with-capped-issuance)|Discusses a reward curve with *capped* issuance, as opposed to *tempered* issuance.|🤯&#160;🤯|
|[FAQ: Ethereum issuance reduction](https://ethresear.ch/t/faq-ethereum-issuance-reduction/19675)|Anders answers 8 FAQs in the debate around a reduction in issuance.|🤯&#160;🤯|

#### *by [Mike](https://twitter.com/mikeneuder)*
|Title|Description|🤯?|
|-----|-----------|----------|
|[Issuance Issues — Initial Issue](https://notes.ethereum.org/@mikeneuder/iiii)|Mike's distillation of issuance debate and why to change issuance policy.|🤯|
|[Issuance Issues — Subsequent Soliloquy](https://notes.ethereum.org/@mikeneuder/subsol)|Walks through a key point of the issuance endgame(tm) post to provide more intuition: why real issuance yield can be higher in the long term equilibrium, despite a reduced (!) issuance policy.|🤯&#160;🤯|
|[Issuance Issues — Tertiary Treatise](https://hackmd.io/@mikeneuder/iitt)|Mike provides more intuition for why the burn (EIP-1559) is orthogonal to the issuance discussion|🤯&#160;🤯|

#### *by [Julian](https://twitter.com/_julianma)*
|Title|Description|🤯?|
|-----|-----------|----------|
|[Initial Analysis of Stake Distribution](https://ethresear.ch/t/initial-analysis-of-stake-distribution/19014)|It presents a minimum non-trivial model to analyze the distribution of stake with respect to the level of issuance.|🤯&#160;🤯&#160;🤯|

### Talks
|Title|Speaker(s)|Conference, Date|🤯?|
|-----|-------|----------------|---|
|[Ethereum Staking Economics Endgame](https://www.youtube.com/watch?v=mayktOkDTRg&t=1755s)|Ansgar|[EthDubai, 20 Apr 2024](https://twitter.com/adietrichs)|🤯&#160;🤯|
|[Issuance Panel](https://www.youtube.com/live/g7PK1RiK2Mg?si=cB6GermCD37NeHhW&t=1542)|Ansgar, nixo, & dapplion|[DappCon, 22 May 2024](https://twitter.com/adietrichs)|🤯|
|[issued issues](https://t.co/nc8NHaPj4b)|Caspar|[ZuBerlin, 12 Jun 2024](https://twitter.com/casparschwa)|🤯|

### Podcasts
|Podcast: Title|Guest(s), Host(s)|Date|🤯?|
|--------------|-----------------|------------|---|
|[Uncommon Core 2.0: Ethereum's Staking Endgame](https://open.spotify.com/episode/2YhHNjUwj44F1C3LXcCP0N?si=YmbgzZwcRTqaYVct6AzkfA) (also on [YouTube](https://www.youtube.com/watch?v=ivynR3RI3_Y))|*with Ansgar & Caspar, hosted by Hasu & Jon*|22 Mar 2024|🤯&#160;🤯|
|[Bankless: ETH Monetary Policy: The Issuance Debate](https://www.youtube.com/watch?v=GLP_qRyPuv4)|*with David & Ryan*|10 Apr 2024|🤯|
|[Infinite Jungle: Is Ethereum Printing Too Much ETH?](https://youtu.be/qw4Kp8UPBv0?si=WoUM2FkgfgdfOSUu)|*with nixo, hosted by Christine*|10 Apr 2024|🤯|
|[Epicenter: Ethereum Staking Wars with EthStaker](https://www.youtube.com/watch?v=2krlPcbpZvQ)|*with nixo & superhiz, hosted by Friederike*|7 Jun 2024|🤯|


### Misc
This is a collection of less dedicated writings/discussions found on Twitter or relevant snippets from talks/podcasts. This list is *not* exhaustive. 

|Type|Author|Title|🤯?|
|----|------|-----|---|
|Paper|Urban Jermann|[A Macro Finance Model for Proof-of-Stake Ethereum](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4335835)|🤯&#160;🤯&#160;🤯|
|Post|Brett Palatiello|[Towards a holistic formalization of ETH](https://bmpalatiello.github.io/2023/06/16/formalization-of-eth.html)|🤯&#160;🤯&#160;🤯|
|Podcast clip|Oisín, hosted by Christine|[Infinite Jungle: Is There Too Much ETH Staked? Devs Weigh Reduction In Staking Rewards](https://www.youtube.com/watch?v=LbkxL-xBYYE&list=PLz3vbkrzRoXR_XIWVqnZcX11REeC6acN2&index=26)|🤯|
|Podcast clip|nixo, hosted by Christine|[Infinite Jungle: Ethereum Devs Debate Account Abstraction EIPs for Electra](https://youtu.be/EAgAAXJIx7I?si=-Qsbu0sQHykFfV4S&t=1425)|🤯|
|Twitter|Artem|[Artem's counter-arguments to changing Ethereum issuance](https://twitter.com/artofkot/status/1775632385414959331)|🤯|
|Podcast clip|David & Anthony|[Bankless Clips: ETH Monetary Policy: The Issuance Debate](https://www.youtube.com/watch?v=iXNtNXy7sxU)|🤯|
|Podcast clip|David & Ryan|[Bankless Clips: What’s Next for ETH Monetary Policy?](https://www.youtube.com/watch?v=-ihs12qAoY8)|🤯|
|Podcast clip|Sreeram, hosted by Myles & Mike|[Bell Curve: Exploring EigenLayer and The Future of Ethereum Security](https://youtu.be/ozvMIydgcKs?si=t-YD59a1p3vUN5qn&t=5965)|🤯|
