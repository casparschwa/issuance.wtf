# issuance.wtf

#### This document aims to collect resources relevant to Ethereum's current issuance discussion.

*This page is maintained and kept ~up-to-date\~ by [Caspar](https://twitter.com/casparschwa). Feel free to ping with questions/comments/requests on Twitter or Telegram @casparschwa, and please point out missing resources.*

Last updated: 03/10/2025.

# Introduction

Ethereum's issuance policy is effective at ensuring a minimum level of staking and thereby economically guaranteeing reasonable security.

However, the current issuance policy has effectively no control over the upper limit of stake participation. A too high staking ratio, (staked ETH / total ETH), comes with downsides that need to be considered carefully.

For this reason, proposals to change Ethereum's issuance policy were put forward and are currently discussed.

The goal of this document is to collect resources (writeups/talks/podcasts/etc.) relevant to Ethereum's *current* issuance discussion.

# Highlights
*Disclaimer: This section is <u>subjective</u>. Please take a look at the following section for a more exhaustive and unopinionated list of resources.*

For an overview on the current issuance debate, the following resources are a good starting point; in \~rough\~ order of suggested consumption:

### Technical highlights (> 🤯)
1. [Ansgar](https://twitter.com/adietrichs) & [Caspar's](https://twitter.com/casparschwa) [issuance endgame™ post](https://ethresear.ch/t/endgame-staking-economics-a-case-for-targeting/18751) explores why Ethereum is plausibly heading towards a very high % stake evnvironment under its current issuance policy; it then argues for why this future is problematic, and suggests to *target* a low staking ratio in the issuance endgame. Alternatively, watch this talk by same authors focuses on *why* to change the issuance policy: ["Is Ethereum’s Issuance Policy Sustainable?"](https://ethcc.io/archive/Is-Ethereums-Issuance-Policy-Sustainable) focuses on *why* to change the issuance policy, i.e. problems of high % staked environments.
3. [Anders'](https://twitter.com/weboftrees) [master piece](https://ethresear.ch/t/properties-of-issuance-level-consensus-incentives-and-variability-across-potential-reward-curves/18448/) proposes and analyzes new reward curve(s) with tempered issuance. Beyond the specific curve(s), it is a valuable resource to learn about relevant properties when considering issuance curves. Note that in broad strokes, Anders considers this proposed issuance policy to be viable for the endgame, while Ansgar&Caspar consider it a great *short term* issuance policy before moving to a stake ratio targeting policy for the endgame. 
4. [Mike's](https://twitter.com/mikeneuder) [second Issuance Issues](https://notes.ethereum.org/@mikeneuder/subsol) takes the time it deserves to provide more intuition for a key point of the issuance endgame™ post: why *real* issuance yield can be higher in the long term equilibrium, despite a reduced (!) issuance policy.
5. [Anders'](https://twitter.com/weboftrees) deep-dive on his [thinking about the trade-offs](https://ethresear.ch/t/faq-ethereum-issuance-reduction/19675) when exploring various potential issuance policies in an FAQ format. Note that Anders' views differ to Ansgar&Caspar's in <u>some</u> aspects, e.g. desirable staking ratio target or viability of non-targeting policies for the endgame. 
6. If you prefer podcast format, this [Uncommon Core episode](https://open.spotify.com/episode/2YhHNjUwj44F1C3LXcCP0N?si=YmbgzZwcRTqaYVct6AzkfA) (also on [YouTube](https://www.youtube.com/watch?v=ivynR3RI3_Y)) is your 2.5h one-stop solution. It outlines most of [Ansgar](https://twitter.com/adietrichs) & [Caspar's](https://twitter.com/casparschwa) thinking behind the issuance endgame™ post + productive debate with Hasu&Jon.

### High-level highlights (= 🤯)
1. [Ansgar](https://twitter.com/adietrichs)&[Caspar](https://twitter.com/casparschwa)'s talk ["Is Ethereum’s Issuance Policy Sustainable?"](https://ethcc.io/archive/Is-Ethereums-Issuance-Policy-Sustainable) focuses on *why* to change the issuance policy, i.e. problems of high % staked environments.
2. [Mike's](https://twitter.com/mikeneuder) [Initial Issue](https://notes.ethereum.org/@mikeneuder/iiii) is a more high-level take on the endgame post™ and presents his view on the matter.
3. In this [Bankless episode](https://www.youtube.com/watch?v=GLP_qRyPuv4) [David](https://twitter.com/TrustlessState) & [Ryan](https://twitter.com/RyanSAdams) "give a masterclass on monetary policy for Ethereum and beyond".
4. In this [Epicenter episode](https://www.youtube.com/watch?v=2krlPcbpZvQ) [nixo](https://twitter.com/nixorokish) & [superhiz](https://twitter.com/superphiz) from EthStaker talk about the issuance debate with a focus on the solo staker perspective.

# Exhaustive list of resources
## Writings
| Author | Title | Description | Type | Date | 🤯? |
|--------|-------|-------------|------|------|-----|
| [Anders](https://twitter.com/weboftrees) | [Minimum Viable Issuance](https://notes.ethereum.org/@anderselowsson/MinimumViableIssuance) | Long thread arguing for minimum viable issuance to be an important pledge to the regular Ethereum user. | Post | 7 Oct 2023 | 🤯🤯 |
| [Anders](https://twitter.com/weboftrees) | [Properties of issuance level: consensus incentives and variability across potential reward curves](https://ethresear.ch/t/properties-of-issuance-level-consensus-incentives-and-variability-across-potential-reward-curves/18448/) | Analyzes the effect of issuance level on consensus incentives and reward variability across potential reward curves. Recommends decreasing issuance at high staking levels, by changing the issuance curve from cF√D to cF√D(1+kD). | Post | 24&#160;Jan 2024 | 🤯&#160;🤯&#160;🤯 |
| [Ansgar](https://twitter.com/adietrichs) & [Caspar](https://twitter.com/casparschwa) | [Endgame Staking Economics: A case for targeting](https://ethresear.ch/t/endgame-staking-economics-a-case-for-targeting/18751) | Explores the past, current and probable future of staking levels, what negative externalities of too much stake are, and argues for why targeting a low % of stake is desirable as the endgame issuance policy. | Post | 22 Feb 2024 | 🤯🤯 |
| [Ansgar](https://twitter.com/adietrichs)&#160;& [Caspar](https://twitter.com/casparschwa) | [Electra: Issuance Curve Adjustment Proposal](https://ethereum-magicians.org/t/electra-issuance-curve-adjustment-proposal/18825) | Short-term proposal to lower issuance curve from cF√D to cF√D(1+kD) as proposed and analyzed by Anders. This adjustment is proposed as an intermediate step toward the envisioned endgame: stake targeting. | Post | 22 Feb 2024 | 🤯🤯 |
| [Julian](https://twitter.com/_julianma) | [Initial Analysis of Stake Distribution](https://ethresear.ch/t/initial-analysis-of-stake-distribution/19014) | It presents a minimum non-trivial model to analyze the distribution of stake with respect to the level of issuance. | Post | 15&#160;Mar 2024 | 🤯&#160;🤯&#160;🤯 |
| [Mike](https://twitter.com/mikeneuder) | [Issuance Issues — Initial Issue](https://notes.ethereum.org/@mikeneuder/iiii) | Mike's personal distillation of issuance debate and why to change issuance policy. | Post | 30&#160;Mar 2024 | 🤯 |
| [Anders](https://twitter.com/weboftrees) | [Reward curve with tempered issuance: EIP research post](https://ethresear.ch/t/reward-curve-with-tempered-issuance-eip-research-post/19171) | Aims to present the rationale for a reward curve with tempered issuance, i.e., cF√D(1+kD). | Post | 1 Apr 2024 | 🤯🤯🤯 |
| [Anders](https://twitter.com/weboftrees) | [Foundations of minimum viable issuance](https://notes.ethereum.org/@anderselowsson/Foundations-of-MVI) | Takes a closer look at the dynamics of cost and surplus in staking, demonstrating how all token holders can benefit from reduced issuance. | Post | 17&#160;Apr 2024 | 🤯 |
| [Anders](https://twitter.com/weboftrees) | [Reward curve with capped issuance](https://notes.ethereum.org/@anderselowsson/Reward-curve-with-capped-issuance) | Discusses a reward curve with *capped* issuance, as opposed to *tempered* issuance. | Post | 18&#160;Apr 2024 | 🤯🤯 |
| [Mike](https://twitter.com/mikeneuder) | [Issuance Issues — Subsequent Soliloquy](https://notes.ethereum.org/@mikeneuder/subsol) | Walks through a key point of the issuance endgame™ post argument-by-argument to provide more intuition: why real issuance yield can be higher in the long term equilibrium, despite a reduced (!) issuance policy. | Post | 11&#160;May 2024 | 🤯🤯 |
| [Anders](https://twitter.com/weboftrees) | [FAQ: Ethereum issuance reduction](https://ethresear.ch/t/faq-ethereum-issuance-reduction/19675) | Anders answers 8 FAQs in the debate around a reduction in issuance. | Post | 29&#160;May 2024 | 🤯🤯 |
| [Mike](https://twitter.com/mikeneuder) | [Issuance Issues — Tertiary Treatise](https://hackmd.io/@mikeneuder/iitt) | Provides more intuition for why the burn (EIP-1559) is orthogonal to the issuance discussion. | Post | 21&#160;Jun 2024 | 🤯🤯 |
[Artem](https://x.com/artofkot), [damcnuta](https://x.com/damcnuta), [Sonya](https://x.com/sonyasunkim) & [adcv_](https://x.com/adcv_) | [Maximum Viable Security: A New Framing for Ethereum Issuance](https://ethresear.ch/t/maximum-viable-security-a-new-framing-for-ethereum-issuance/19992/1) | Proposes shifting focus from minimizing issuance to maximizing security (in terms of ETH staked), arguing that issuance reductions could increase centralization risks.| Post | 06 Jul 2024 | 🤯🤯
[pa7x1](https://ethresear.ch/u/pa7x1/summary) | [The Shape of Issuance Curves to Come](https://ethresear.ch/t/the-shape-of-issuance-curves-to-come/20405/1) | This post analyzes the effects of different Ethereum issuance curves on decentralization.| Post | 10 Sept 2024 | 🤯🤯
[Vitalik](https://x.com/VitalikButerin) | [Possible futures of the Ethereum protocol, part 3: The Scourge](https://vitalik.eth.limo/general/2024/10/20/futures3.html) | This post talks about The Scourge part of the Ethereum roadmap. In particular, it touches on the topic of staking economics, in which he lays out the tradeoffs of various paths forward.| Post | 20 Oct 2024 | 🤯
| [Anders](https://twitter.com/weboftrees) | [Practical endgame on issuance policy](https://notes.ethereum.org/@anderselowsson/ByGsJOVCC) | This post outlines a practical endgame on issuance policy, presenting reward curves that adhere to requirements of the consensus protocol and can reduce yearly issuance so that the quantity of stake stops growing in the near future. | Post | 1 Apr 2024 | 🤯🤯|
| Eric Downes |[Ethereum Macroeconomics via Dynamics](https://ethresear.ch/t/ethereum-macroeconomics-via-dynamics/21539/1)| The post introduces a dynamic systems approach to modeling Ethereum’s economic parameters, focusing on how staking and economic incentives impact long-term equilibrium conditions. | Post | 21 Jan 2025| 🤯&#160;🤯|
| [Antero Eloranta](https://x.com/antsae_), [Santeri Helminen](https://x.com/0xSanteri)|[Impact of Consensus Issuance Yield Curve Changes on Competitive Dynamics in the Ethereum Validator Ecosystem](https://ethresear.ch/t/impact-of-consensus-issuance-yield-curve-changes-on-competitive-dynamics-in-the-ethereum-validator-ecosystem/21617) |This post analyzes how changes in Ethereum’s issuance yield curve influence validator competitiveness and market structure, particularly affecting large-scale staking entities. | Post | 28 Jan 2025 |🤯&#160;🤯 |
| [Vivian Zhu](https://x.com/vivzhuu), [Otakar Korinek](https://x.com/OtakarKorinek), [Alex Duckworth](https://x.com/0xDuckworth)|[ETH Issuance Discovery Research: Issuance Debate & Case Studies By Staking Cohort](https://ethresear.ch/t/eth-issuance-discovery-research-issuance-debate-case-studies-by-staking-cohort/21664) | The post explores case studies of different staking cohorts to understand how varying issuance policies impact validator profitability, behavior, and overall network decentralization. | Post | 4 Feb 2025 | 🤯 |

## Talks
| Speaker(s) | Title | Conference | Date | 🤯? |
|------------|-------|------------|------|-----|
| [Ansgar](https://twitter.com/adietrichs) | [Ethereum Staking Economics Endgame](https://www.youtube.com/watch?v=mayktOkDTRg&t=1755s) | EthDubai | 20 Apr 2024 | 🤯&#160;🤯 |
| [Ansgar](https://twitter.com/adietrichs), [nixo](https://twitter.com/nixorokish), & [dapplion](https://twitter.com/dapplion) | [Issuance Panel](https://www.youtube.com/live/g7PK1RiK2Mg?si=cB6GermCD37NeHhW&t=1542) | DappCon | 22 May 2024 | 🤯 |
| [Caspar](https://twitter.com/casparschwa) | [issued issues](https://t.co/nc8NHaPj4b) | ZuBerlin | 12 Jun 2024 | 🤯 |
| [Ansgar](https://twitter.com/adietrichs), [Caspar](https://twitter.com/casparschwa) & [Christine](https://twitter.com/christinedkim) | [Talk/Discussion: What's the issue with issuance?](https://ethcc.io/archives/whats-the-issue-with-issuance) | EthStaker&#160;@EthCC | 08 July 2024 | 🤯 |
| [Ansgar](https://twitter.com/adietrichs) & [Caspar](https://twitter.com/casparschwa) | [restaking-burn](https://www.youtube.com/watch?v=xXqXoZbP_Ew) | Restaking Day | 09 July 2024 | 🤯🤯 |
| [Ansgar](https://twitter.com/adietrichs) & [Caspar](https://twitter.com/casparschwa) | [Is Ethereum’s Issuance Policy Sustainable?](https://ethcc.io/archives/is-ethereums-issuance-policy-sustainable) | EthCC | 11 July 2024 | 🤯 |


## Podcasts
| Podcast | Guest(s), Host(s) | Title | Date | 🤯? |
|---------|-------------------|-------|------|-----|
| Uncommon Core 2.0 | with [Ansgar](https://twitter.com/adietrichs) & [Caspar](https://twitter.com/casparschwa), hosted by [Hasu](https://twitter.com/hasufl) & [Jon](https://twitter.com/joncharb) | [Ethereum's Staking Endgame](https://open.spotify.com/episode/2YhHNjUwj44F1C3LXcCP0N?si=YmbgzZwcRTqaYVct6AzkfA) | 22&#160;Mar&#160;2024 | 🤯&#160;🤯 |
| Bankless | with [David](https://twitter.com/TrustlessState) & [Ryan](https://twitter.com/RyanSAdams) | [The Debate Over ETH's Monetary Policy](https://www.youtube.com/watch?v=GLP_qRyPuv4) | 10 Apr 2024 | 🤯 |
| Infinite Jungle | with [nixo](https://twitter.com/nixorokish), <br /> hosted by [Christine](https://twitter.com/christinedkim) | [Is Ethereum Printing Too Much ETH?](https://youtu.be/qw4Kp8UPBv0?si=WoUM2FkgfgdfOSUu) | 10 Apr 2024 | 🤯 |
| Epicenter | with [nixo](https://twitter.com/nixorokish) & [superhiz](https://twitter.com/superphiz), hosted by [Friederike](https://twitter.com/tw_tter) | [Ethereum Staking Wars with EthStaker](https://www.youtube.com/watch?v=2krlPcbpZvQ) | 7 Jun 2024 | 🤯 |


## Misc
This is a collection of relevant writings/discussions/musings found on Twitter or relevant snippets from talks/podcasts. This list is *not* exhaustive. 

| Type | Title | Author/Speaker | Date | 🤯? |
|------|-------|----------------|------|-----|
| Paper | [A Macro Finance Model for Proof-of-Stake Ethereum](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4335835) | [Urban](https://fnce.wharton.upenn.edu/profile/jermann/) | 25 Jan 2023 | 🤯&#160;🤯&#160;🤯 |
| Post | [Towards a holistic formalization of ETH](https://bmpalatiello.github.io/2023/06/16/formalization-of-eth.html) | [Brett](https://twitter.com/brettpalatiello) | 16 Jun 2023 | 🤯&#160;🤯&#160;🤯 |
| Podcast clip | [Infinite Jungle: Is There Too Much ETH Staked? Devs Weigh Reduction In Staking Rewards](https://www.youtube.com/watch?v=LbkxL-xBYYE&list=PLz3vbkrzRoXR_XIWVqnZcX11REeC6acN2&index=26) | with [Oisín](https://twitter.com/OisinKyne), hosted by [Christine](https://twitter.com/christinedkim) | 27 Feb 2024 | 🤯 |
| Podcast clip | [Infinite Jungle: Ethereum Devs Debate Account Abstraction EIPs for Electra](https://youtu.be/EAgAAXJIx7I?si=-Qsbu0sQHykFfV4S&t=1425) | with [nixo](https://twitter.com/nixorokish), hosted by [Christine](https://twitter.com/christinedkim) | 5 Mar 2024 | 🤯 |
| Tweet | [Artem's counter-arguments to changing Ethereum issuance](https://twitter.com/artofkot/status/1775632385414959331) | [Artem](https://twitter.com/artofkot) | 3 Apr 2024 | 🤯 |
| Podcast clip | [Bankless Clips: ETH Monetary Policy: The Issuance Debate](https://www.youtube.com/watch?v=iXNtNXy7sxU) | with [David](https://twitter.com/TrustlessState) & [Anthony](https://twitter.com/sassal0x) | 8 Apr 2024 | 🤯 |
| Podcast clip | [Bankless Clips: What’s Next for ETH Monetary Policy?](https://www.youtube.com/watch?v=-ihs12qAoY8) | with [David](https://twitter.com/TrustlessState) & [Ryan](https://twitter.com/RyanSAdams) | 22 Apr 2024 | 🤯 |
| Post | [Sacha's Thoughts on MVI](https://hackmd.io/@sacha/thoughts-on-mvi) | [Sacha](https://twitter.com/lazyleger) | 24 Apr 2024 | 🤯 |
| Tweet | [Philosophical musings by Sacha](https://x.com/lazyleger/status/1783171166774968355) | [Sacha](https://twitter.com/lazyleger) | 24 Apr 2024 | 🤯 |
| Podcast clip | [Bell Curve: Exploring EigenLayer and The Future of Ethereum Security](https://youtu.be/ozvMIydgcKs?si=t-YD59a1p3vUN5qn&t=5965) | with [Sreeram](https://twitter.com/sreeramkannan), hosted by [Myles](https://twitter.com/MylesOneil) & [Mike](https://twitter.com/MikeIppolito) | 28 May 2024 | 🤯 |
| Tweet | [Croissant issuance curve](https://x.com/drakefjustin/status/1887108667675124174) | [Justin](https://x.com/drakefjustin/)| 5 Feb 2025 | 🤯 |
