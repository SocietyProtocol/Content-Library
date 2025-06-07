---
created: 2025-04-17T11:15
updated: 2025-06-05T20:56
---
Let's start with a simple assumption: **the price of assets is influenced by the group of entities owning that asset**. To verify this, please run a simple thought experiment:

- Would the price of gold be the same today if one entity owned all the gold in the world?
- Would Microsoft's stock price be the same if Bill Gates' stake was distributed among America's homeless population?
- Would the price of the Mona Lisa be the same if its creator and previous owners were all working-class peasants? 

Everything that follows in this article hinges on this assumption: _a change in ownership structure fundamentally transforms asset valuation_. This principle applies universally to all asset classes—from commodities to collectibles. **The set of entities owning an asset changes the valuation of that asset.**

Many implications can be drawn from this: that decentralization matters, why ownership history carries significant meaning, and why venture capitalists obsess over co-investment partners. However, let’s focus on one particularly important implication: current blockchain architectures lack transparency around ownership set and robust sybil-resistance to stop the manipulation of ownership sets – make them **irreparably** unsuitable tools for participants to perceive the true <u>token valuations</u>, <u>security provided</u>**,** <u>governance participants</u>, and their <u>true coordination</u> (which occurs at the social layer).

**It gets worse**, economic game theory stipulates that participants are incentivized to form cabals and manipulate these perceptions to reap economic rewards. This is called <u>decentralization theater</u>. Another conclusion can be drawn (and practically observed if you peer close enough in this industry): every asset blockchain is a cabal of insiders manipulating the perception of ownership set for economic benefit as this behavior is the game theory optimal strategy. **Therefore, blockchains can never live up to their decentralized vision**, because the value of every asset is not only imperceptible without understanding the social layer but also always manipulated by a cabal of insiders underneath.

**This situation isn’t something that we have to watch out for once** (such as collusion during the trusted setup of zk-snarks [@vitalikbuterinHowTrustedSetups2022]), it’s something that can happen at any point during the lifetime of a network, persists silently (as cabals do) in the system, and also happens to be the default starting state for any of these systems with participants who understand game theory.

While these dynamics are always theoretically costly to ordinary participants, let's combine theory with practice and explore some catastrophic scenarios. _This article is neither a condemnation of the entities involved, nor a pessimistic article. It underlies a systematic issue in blockchain networks that we have resolved at Society Protocol._

## Fake Assets (Valuation)

Market participants perceive asset valuations through the lens of global markets…yet these valuations are _easily manipulated_ with permissionless sybil attacks. **True valuations must include the true ownership set.** Since blockchain networks do not have sybil resistance, we cannot make assertions or trust in the decentralization of the ownership set, and **therefore the asset valuation itself–making sound money impossible**.

Visualization of ownership categories:

![|700](https://lex-img-p.s3.us-west-2.amazonaws.com/img/cac7d887-fed2-48b7-a0c2-f3f402622d7e-RackMultipart20250414-147-yf09s6.png)

Caption: _Participants want the other people co-holding the same assets to be in rich & stable category. The last thing they want to find out; is that their assets are only co-owned by some dude living in his mother's basement and she's about to kick him out!_

### Fake Transactions

> Blockchain networks face a dual mandate. They need transaction fees to prevent spam transactions, yet must minimize these same fees to remain efficient. This creates a fundamental problem: the cost of forging participants is merely the cost of transactions in the network.

News sources consistently publish a slew of articles about the staggering volumes of decentralized tokens, stablecoins, and perpetuals to the public.

- [Stablecoin Volumes Surpassed Visa & Mastercard Combined In 2024](https://www.zerohedge.com/crypto/stablecoin-volumes-surpassed-visa-mastercard-combined-2024)
- [Stablecoins: the real crypto craze](https://www.economist.com/finance-and-economics/2025/02/23/stablecoins-the-real-crypto-craze)
- [Hyperliquid flips Solana in fees, but is the ‘HYPE’ justified?](https://cointelegraph.com/news/hyperliquid-flips-solana-in-fees-but-is-the-hype-justified?utm_source=rss_feed&utm_medium=rss&utm_campaign=rss_partner_inbound)
- [**Pump.fun’s new DEX reaches $1B volume a week after launch**](https://cointelegraph.com/news/pumpswap-trading-volume-1-billion-pumpfun-memecoin-decline?utm_source=feedly_feed&utm_medium=rss&utm_campaign=rss_partner_inbound)

**These volume comparisons are fundamentally misleading.** Traditional payment networks like Visa & Mastercard operate under entirely different economic constraints than blockchain networks. Each Visa transaction incurs a ~2.9% + 30¢ fee, creating a substantial economic barrier against fake volume. Generating $1 million in fabricated transactions would cost roughly $30,000 in fees. This economic friction naturally filters out artificial activity. Blockchain networks, by contrast, might charge mere cents or even fractions of a penny per transaction. On modern networks like Solana, creating $1 million in fake volume might cost less than $10 in fees—a negligible cost that creates virtually no barrier to fabrication. This fundamental difference in economic design means blockchain volume statistics are trivially manipulated, rendering them meaningless as indicators of genuine economic activity.

### Let’s explore a theoretical scenario:

A well-connected entrepreneur named Tron Kwon launches a new “Famous Coin.” At launch:

  1. The Famous Coin community appears incredibly active with over 100,000 participants chatting and sending transactions.
  2. It is supported by 10,000 validators maintaining network security.
  3. Famous Coin becomes listed on both centralized and decentralized exchanges at a $10 trillion valuation, with daily volume also reaching $10 trillion.
  4. After launching, Famous Coin persists in this state for a period of 10 years.

By all observable metrics, Famous Coin has become the largest asset in the world overnight. It dominates headlines, reaches billions of eyeballs, and demonstrates all the statistical hallmarks of legitimacy: a massive market cap, astronomical volume, a vibrant community, and an extensive validator network.

The disturbing truth is that this entire ecosystem can be fabricated, and the cost is <u>minimal</u>. While this exact $10 trillion scenario hasn't occurred, it's not because of technical limitations—it's because such an extreme case would invite immediate scrutiny. However, _more subtle versions of this manipulation happen regularly_.

There are essentially no technical barriers to forging asset valuation, volume, validators, and community engagement. Creating fake participants costs merely the transaction fees required by the network. Those "100,000 active community members" can be generated by a combination of AI bots and a small team of operators in low-wage regions managing thousands of accounts. Exchange listings can be secured through backroom deals with centralized platforms or by using decentralized exchange mechanisms. The price of an asset is what the entities owning the supply say it is.

The costs of maintaining this deception are negligible compared to the perceived value being created. Tron Kwon controls the supply and can sustain the illusion for years while gradually extracting real value from genuine participants who enter the ecosystem.

If participants can't trust asset valuations, community size, or transaction volume in blockchain networks, what metrics can users trust? The uncomfortable answer is: **none.** Participants can only trust in the strength of the cabal.

### Let’s explore a real world example:

> In November 2022, a leaked balance sheet revealed that Alameda Research, a trading firm also run by Bankman-Fried, held a massive amount of FTX’s native token, FTT, and was using customer funds for risky bets. This exposed FTX’s centralized mismanagement—Bankman-Fried effectively treated the exchange and Alameda as one entity, with no real separation. When rival Binance announced it would dump its FTT holdings, panic ensued, and FTX faced a bank run it couldn’t survive. FTT’s price crashed from $25 to under $2 in days, a 90%+ drop, wiping out $2 billion in market cap. FTX filed for bankruptcy, and customer assets worth billions were frozen.

* * *

**The bottom line is very simple:** participants can’t see who truly owns these assets, and therefore—can’t know what they’re actually worth.

## Fake Security (Trust)

The security in blockchains derives in a few common ways, these are Proof of Work (PoW), Proof of Stake (PoS), and Threshold Signature Schemes (TSS). Each of these systems offers a distinct security paradigm, but their effectiveness depends on factors that might not be obvious to participants. _Let's examine the underlying assumptions of each security model._

### **Proof of Work** **\[POW\]**

The amount of security in PoW derives from having an amount of computing power which is strong enough to protect the network against 51% attacks on the network.

1. How do participants know which network is valuable enough to secure with all this computing power, and which one to abandon? **The asset valuation.**
2. How do participants know the asset valuation? _Let’s refer back to the Fake Assets (Valuation)_ section…**They don’t.**
3. Since participants can’t accurately value the asset, they can’t know what its security is. **The network’s security becomes imperceptible.**

**There are two more quirks:**

1. Networks which fall in asset value in the PoW world are exposed to a death spiral effect (where computing power can switch over from other stronger networks and 51% attack their network) – occupying a secondary position with compatible mining hardware creates an existential vulnerability.
2. PoW compute capacity naturally aggregates over time, placing >51% of the power in the hands of a few participants. _<u>These entities don't attack the network not because they can't, but because doing so would undermine their own economic interests</u>._ Bitcoin, the largest and most stable PoW network, exists at the behest of 2-4 mining pool entities. PoW is only secure as long as the synchronized state makes sense for the cabal to maintain. Should this economic equation ever change—due to market crashes, regulatory pressure, or external incentives—these entities would collapse the entire system overnight. The precipice is ever-present, a single successful 51% attack orchestrated by this small cabal would permanently shatter trust in the system initiating a catastrophic death spiral.

**What a perilous way to secure our entire future financial system!**

This has of course all happened numerous times in practice:

> Bitcoin Satoshi's Vision (BSV) provides a striking real-world example of security collapse. After peaking at a valuation of $9.1 billion in April, by July and August of 2021, BSV suffered multiple devastating 51% attacks where malicious actors gained control of the majority of network hash power, allowing them to double-spend coins and reorganize over 100 blocks. These attacks weren't particularly expensive—costing merely thousands of dollars per hour—yet they permanently destroyed trust in the network. Exchanges immediately halted BSV deposits and withdrawals, liquidity evaporated, and market capitalization plummeted by over 70%. BSV never recovered its credibility or market position. The network continues operating today as a hollow shell, with minimal economic activity and catastrophically reduced security, perfectly illustrating how quickly the illusion of decentralized security can collapse.

### Proof of Stake \[POS\]

The amount of security in PoS is derived <u>directly from the token value</u>. It takes 51% of the tokens to attack and corrupt a network. Since participants cannot ever accurately perceive the token valuation, the amount of security in PoS might as well be “Magic number X”. **Participants are unable to determine whether their assets are secure or not.**

Most PoS secured blockchains build extensive ecosystems of centralized and decentralized assets on their platforms, all of which rely on the underlying network for security. Since participants cannot accurately perceive the amount of security of the underlying network, all of these assets become at risk; all the time.

There is another big problem: PoS networks also suffer from similar centralization effects as PoW mining pools, where 2-3 staking pools maintain a >51% stake in the network and can collude at any time to corrupt the network—ruining its perceived security forever. Ethereum, the largest and most stable PoS network state, exists at the behest of 2-4 staking pool entities. The same exact scenario plays out as in PoW (but without the mining compute equipment, so it’s more green). _PoS is only secure as long as the synchronized state makes sense for this cabal to maintain; if it grows unprofitable, they collapse it_.

Where PoS slightly differs from PoW is in that corrupting the network <u>always</u> costs the stakers their perceived token value, whereas in PoW mining, corrupting a network doesn’t necessarily cost the miners any asset value, because the mining and asset is separate.

In practice, this makes finding PoS network 51% collapses rarer, but the principle remains exactly the same—participants exist in the network state at the behest of a cabal. What happens more often is participants gain wind of a 51% possibility and flee (without the cabal profitably corrupting the network):

> EOS, operating on Delegated Proof of Stake (DPoS), faced significant governance issues, notably in 2018 when block producers (BPs) froze seven accounts under orders from the EOS Core Arbitration Forum (ECAF), bypassing transparent on-chain governance, and later with vote-buying allegations involving exchanges like Huobi, suggesting concentrated voting power could control the 21 elected BPs. These incidents resemble a 51% attack because a coordinated group controlling a majority of BPs (11+ of 21) could theoretically manipulate block production, censor transactions, or alter the chain, undermining decentralization. However, they differ from a classic 51% attack as no malicious block production (e.g., double-spending) occurred. The consequences included eroded trust, reduced voter participation (dropping to ~10% of tokens by 2019), and a decline in EOS’s market relevance.

### Threshold Signature Schemes \[TSS\]

TSS derives its security from a separation of owners by splitting the cryptographic key into multiple pieces, thereby requiring multiple blockchain accounts to sign a transaction.

Since blockchains do not have sybil-resistance, participants cannot know who controls all these accounts. Anything from a 2/2 to a 2 quadrillion/2 quadrillion TSS can all be owned by one entity, or a cabal. Participants looking from the outside at the security of TSS schemes **cannot ever accurately perceive the amount of security**.

There are, of course multiple high-profile examples of users’ trust in multi-sig schemes only to find out their security was an illusion…it was provided by the cabal until it either a) got hacked or b) decided to steal the money. The cabal doesn’t necessarily have to be malicious, it could just get hacked or compromised as in our real-world example:

> In July 2023, Multichain, a cross-chain bridge protocol, collapsed after a $126 million exploit drained its liquidity pools, halting operations across 25+ blockchains, with the crisis exacerbated by the reported arrest of its CEO in China, which cut the core team’s access to servers and operational wallets, revealing a governance failure akin to a 51% attack’s disruption but driven by centralized control rather than consensus manipulation. Multichain used a Threshold Signature Scheme (TSS) distributing private key shares among nodes (e.g., 9-of-15) to sign transactions, but its implementation was centralized as the core team retained critical operational control. This centralization was exposed when the team admitted post-hack that only they could access bridge servers.

* * *

What's particularly concerning is that while these security models appear robust on paper, they all share a critical vulnerability. **They fundamentally depend on the very ownership structures we've established are imperceptible**. The security guarantees blockchain networks trumpet—immutability, censorship-resistance, and trustlessness—all depend on asset ownership[^1]. This isn't just theoretical; it constantly manifests in catastrophic real-world failures that expose the fragility beneath the surface.

By now, you can probably see how shaky the foundation of our new financial systems really is. It's constantly shifting, and almost always in one direction: toward more centralized control.

Let's imagine that somehow, a small group (cabal) doesn't control a network at the beginning. Well, that can easily change over time! Once a cabal gains control of a network, going the opposite way isn't that easy. Giving it away is hardly ever game theoretically optimal.

When a cabal controls a network, they have two optimal strategies:

1. "Sheer" - slowly extract value while maintaining the system (like shearing wool from sheep)
2. "Skin" - take everything at once (like killing the sheep for its hide)
3. ~~Give up control of the network, so that your group can no longer do 1 or 2.~~

The worst part? Participants can't tell how secure their assets really are until it's too late. This hidden danger makes these systems fundamentally unreliable. Building our future financial system on security that could vanish without warning is like building a house on fault lines. It doesn't guarantee an earthquake, but they happen!

So, how long are blockchains secure? The cabal maintains a synchronized state, _and as long as they are both willing and able to secure it_, your blockchain is secure. **Participants exist at the behest of the cabal.**

## Fake Governance (People)

Attempts at creating true governance systems and organizations, such as decentralized autonomous organizations (DAOs), on asset based blockchains are **irreparably** impossible due to their non sybil-resistant nature. Anyone can create an unlimited number of identities, which all cost nothing to upkeep, simply by paying transaction fees. This creates an environment where voting cannot be done through verifiable people (_because one person can pretend to be thousands_), and must instead be done via asset ownership…but participants don’t know who owns the assets…therefore, unable to determine their value or the people behind them.

> “Oh, sorry sir. A cabal actually owns the majority of this DAO…no way to prove, no way to perceive. **Sorry, your votes don’t actually count**. We do appreciate you offering feedback, and please have some swag at our next conference, it’s on us!”.

![|300](https://lex-img-p.s3.us-west-2.amazonaws.com/img/29df1a2b-0212-42c2-a127-58a82d072f6c-RackMultipart20250414-124-pmhcck.jpg)

Governance actually functions as a feedback mechanism for the cabal in these organizations. Which isn’t necessarily a bad or a good thing, again we want to reiterate–**you’re investing in the strength of the cabal.**

Of course from their end, the cabal must choose whether to sheer or skin participants. This reflects the age-old wisdom: 'You can shear a sheep many times, but skin it only once.' While shearing provides sustainable returns through fees, informational advantages, and governance control, skinning (through rugpulls, exploits, or abandonment) offers only a single massive payday. That is a difficult life decision, and should not be underestimated.

The game works like this: the longer a cabal can maintain the illusion of decentralization, while making decisions behind the scenes–the longer it can extract valuable informational advantage edges and collect fees from legitimate participants using their system (**sheer**). When the illusion becomes unprofitable, the cabal runs into economic trouble, or it is attacked externally via hacks or game theoretic attacks–collapse the system (**skin**).

### A theoretical shear situation:

A very popular governance model for asset allocation in blockchain ecosystems is public goods funding 🌈, this is where stakeholders in the ecosystem choose which projects to fund (usually from the shared treasury) via voting with their tokens. These sound good in theory, but once we understand cabals are at the center of voting public goods allocation structures, we can realize: all that is truly happening behind the curtain is the cabal is funneling some of the “public treasury” funds to itself and its friends. Keeping the illusion of flow going is the name of the game.

### A real world skin scenario:

- [Polymarket faces scrutiny over $7M Ukraine mineral deal bet](https://cointelegraph.com/news/polymarket-trump-ukraine-bet-whale-governance-attack?utm_source=feedly_feed&utm_medium=rss&utm_campaign=rss_partner_inbound)

In this story, the governance of UMA, an oracle protocol which Polymarket (a prediction markets platform) relies on, decided the outcome of a prediction market falsely via governance vote.

**This scenario has serious implications**: Oracles serve as the critical bridge connecting blockchains to real-world data. Their role is foundational—currently securing over $100 billion in perceived asset value across blockchain ecosystems. To determine the results of real-world events, oracles must use a form of group decision making to arrive at conclusions about the real world—yet blockchains don’t have groups or people— they only store assets. Participants cannot see how much actual security oracles provide because they don’t know who owns these assets.

If an invisible cabal does indeed control the voting apparatus (we need not make definitive assumptions to recognize the structural possibility), they often gain an asymmetric advantage—the luxury of patience. They can maintain the illusion of decentralization for years while methodically selecting only the most lucrative opportunities to reveal their power and "skin" participants. This represents a fundamental governance failure that cannot be patched or reformed within current blockchain architectures.

* * *

### Fake Voting

News sources have published examples of this pattern every week for years, but these articles only illustrate when the cabal is in (skin) mode. The (sheer) mode is happening everyday around us and is undetectable, skinning is only the grand finale. Participants can’t trust in the democratic voting process—they can only trust in the power of the cabal.

- [**Community slams Crypto.com CEO over 70B CRO re-issuance**](https://cointelegraph.com/news/cryptocom-ceo-backlash-70-billion-cro-mint?utm_source=feedly_feed&utm_medium=rss&utm_campaign=rss_partner_inbound)
- [MakerDAO showing itself to be centralized](https://rekt.news/emergency-powers)
- [Hyperliquid forced to reveal invisible centralized kill switch](https://rekt.news/hyperliquidate2)

### Identity Systems

Some people have tried creating verifiable mechanisms to verify asset ownership, such as proof-of-personhood or Know Your Customer (KYC), these very simply don’t work because they don’t impose costs on account existence.

Here’s a quick theoretical example:

- I create an account in 2020, earn many loyalty points and badges…KYC it in my name and it’s fully checked and verified ✅. Nothing prevents me from loaning or selling access to my account at any point in the future. It’s free to indefinitely maintain accounts in the blockchain world. Who owns and controls the account?

## Fake State (Coordination)

The true root of coordination in blockchains always happens underneath at the social layer. This is entirely imperceptible to the asset based blockchain and its participants. Anything built on these blockchains can at any time be invalidated (rugged) by an imperceptible social layer underneath. **What really secures blockchains is a group of people underneath trying to create a synchronized state.**

In most modern networks, often the most powerful and coordinated social layer underneath is the organization which produces and releases updates for the network or application. You see–most blockchains and decentralized applications are still far off from fulfilling their final visions, requiring massive development work behind the scenes. Somebody has to coordinate all this building at the social layer: This group naturally has to be coordinated, organized, and aligned–with shared financial interests. The most powerful cabals in the blockchain world are often found here.

An interesting piece by Haseeb Qureshi [@qureshiEthereumNowUnforkable2019] illustrated a convincing argument that a strong influence in the fork choice of blockchain networks is likely to be ultimately controlled at the social layer by financial entities, and especially centralized entities controlling real-world assets tied to the blockchain like USDT, USDC, and WBTC.

> “In the meantime, DeFi operators watch anxiously. Their hands are tied: they cannot pick sides too early. Why? Because for a DeFi operator, picking the correct fork is critical to their system surviving, and nobody wants to be blamed for instigating additional conflict.” (Qureshi, 2019)

These DeFi operators existing in the state machine <u>must pay attention</u> to the social layer, or risk picking the wrong fork during contentious forks. Which would wipe them out–_yet the social layer is invisible_.

While it would appear that we are talking about fork-choice rule in this section, we are not. **We are talking about social layer coordination**. The social layer does not necessarily need to fork the network to leave.

When the organized social layer decides it’s time to move (fork) or simply not honor the blockchain network–**there is no security, asset valuation, or governance method that will save you**. Either you move with the social layer (which can manipulate or invalidate your assets); or all your assets deriving power from that social layer[^2] will invalidated in the eyes of the group when the social layer leaves the building.

![|750](https://lex-img-p.s3.us-west-2.amazonaws.com/img/ba34986f-3cf2-42d6-a25a-3fe2cac3bc7a-RackMultipart20250414-147-u5cfw4.jpg)

This rule applies any blockchain network and any singular or plural application(s) built on top of it. The social layer, which is assumed to be uncoordinated, but in reality is unevenly coordinated – can simply move to a new ledger and strike you out of the ledger if they are: 1) coordinated enough to do so AND 2) feel like it. This creates another series of perverse incentives for individual actors forming cabals at the social layer and punishments for individuals not being aware of the social layer dynamics (which are fog of war murky due to information flow in real life and politics).

### The best real world example to illustrate this is the Ethereum DAO hard-fork:

> The Ethereum DAO hard-fork occurred in 2016 after hackers exploited a vulnerability to steal $60 million in ETH, forcing the community to choose between immutability and intervention. Despite passionate "code is law" advocates arguing that the blockchain must remain unchanged regardless of consequences, the social consensus overwhelmingly favored human intervention to reverse the theft. Vitalik Buterin and core developers implemented a contentious hard fork that rolled back the blockchain to recover funds, while a minority maintained the original chain as Ethereum Classic. This watershed moment demonstrated the true nature of blockchain governance—that the social layer ultimately determines consensus, not code. The fork established a precedent, human intervention could override "code is law" principles, revealing that decentralized systems ultimately depend on social consensus.

* * *

**What methods do participants have to recover from loss of synchronicity due to collusion at the social layer?**

- **None**. When trust breaks down, there are no transparent tools to visualize dissatisfaction, track migration patterns, or facilitate fork negotiations. The entire process unfolds opaquely, with individuals and groups making decisions at the social layer. Without clear coordination mechanisms to guide participants toward a new synchronized state (akin to switching rails on train tracks), the most powerful social layer cabal inevitably wins—at everyone else's expense. _You must feel the force young jedi._

So if asset blockchains aren’t the real state, what is the real state? The real state is **whatever the social layer decides that it is and synchronizes to**. If tomorrow the entire social layer all wrote down their agreed state on a napkin, and all disappeared to synchronize to that, **that would be the real state.** Blockchains automate the synchronization of state, but do not control the preferred state of potentially coordinated participants. The active blockchain state participants synchronize on can become worthless due to coordinated participants able to switch extremely easily at the cost of uncoordinated social layer participants who cannot see the actions of invisible social layers and all the cabals lurking underneath[^3].

* * *

## **Blockchain can never live up to its reputation or decentralized vision in it’s current form.**

Blockchain started in 2008 as a vision to decentralize the monetary supply with Bitcoin, and expanded in 2015 to decentralize computation with Ethereum. As illustrated above, in its current form it can essentially accomplish neither of these things meaningfully.

**Decentralization as a concept can be broken down into two important functions:**

1. To make the organization lack one central point of failure (distributed)
2. To keep the orgaanization free of power capture capture by a few centralized parties (decentralized)

The world has currently only managed to create <u>distributed</u> synchronized state organizations thus far. While the power sources have become worldwide and hard to track down (able to use opacity and jurisdictional arbitrage), **they are not meaningfully <u>decentralized</u>.**

True decentralization is impeded simultaneously at every layer (valuation, security, governance, and network state) by economic incentives to form cabals. To achieve a path towards meaningfully decentralizing power, we must alter the fundamental design; to remove this irreparable design flaw. **We must transition from web3 to web4**.

## **Are blockchains still valuable?**

Does this mean that Blockchain is a fraud or scam? **Not exactly**…they’re more not exactly what they represent themselves to be (we all wear masks in society, why shouldn’t a network? ).

**The question should really be two-fold:**

1. Are these distributed states governed by a cabal valuable to society?
2. Can the cabal be stopped from convincing a certain percentage of the world’s population to use these tools (whether they are valuable or not)? Meaning, are they valuable to some participants (perhaps they’re a net loss on society but still unstoppable and valuable to some participants).

We must compare it to it’s alternatives. What blockchain offers is worldwide value transmission at the behest of a cabal. Which is kind of similar to what centralized fiat money systems controlled by cartels offer, except there’s less rules and the cabal is more opaque and network based. So it has legitimate conceivable advantages over the fiat system. While the fiat system is run by <u>nation states</u>, blockchains are run by <u>synchronized states</u>. How do they compare against commodities like gold? Let’s take a closer look!

**The cartel (fiat) vs the cabal (crypto) vs the rock (commodities)!**

![](https://lex-img-p.s3.us-west-2.amazonaws.com/img/5444ba14-0790-43b2-a2e6-b464fbf7a351-RackMultipart20250417-132-njpzri.png)

Despite everything we have expoused out about its flaws in this article…it turns out that blockchain based cabal ran <u>synchronized states</u> have legitimate advantages over both fiat and commodities systems! Not only are they likely **unstoppable**, they are also **valuable to society!** These networks are poised to _grow_.

Blockchain networks also serve as the valuable foundational infrastructure for the evolution to Society Protocol. We stand on the shoulders of giants. Many web3 founders are incredible visionaries whose work we deeply respect—they've pioneered an essential evolutionary step in humanity's journey. Some of these founders are heroes to us, rather than dismissing their contributions, we recognize web3 as the necessary predecessor that made our vision possible.

## **The blockchain oligopoly that’s coming. The Cabal:**

If society winds down this path[^4]…what will culminate is a new global financial oligopoly maintained and operated by powerful global cabals. Since these networks do not have real meaningful decentralization, they are often (not always) ticking time bombs (but so are central bank cartels). Its important to understand that investment into cryptocurrency is–**an investment into the power of the cabal**[^5].

The issue is, participants (who are not battling in these cabals), cannot see which is which. The masses have no advantages in either system, they’re playing the lottery. The cabal has the rug rigged. The cabal can pull it, shift it, clean it, move it, or not touch it. **The cabal always maintains control of the rug**.

So civilization is at a critical turning point: we've moved from Web2, where users owned nothing, into Web3, where users believe they own something—but in reality, still don't. To truly progress, we must evolve toward Web4, where ownership isn't an illusion, but a more stable reality. _The cabal can’t rug us…if their lives…are on the blockchain_!

![|700](https://lex-img-p.s3.us-west-2.amazonaws.com/img/c0b51d04-f5e1-44af-a15f-e40da72c5e60-RackMultipart20250417-150-edn5jv.jpg)

## **Society Protocol**

To establish true forms of coordination and valuation, we must bring the social layer on-chain and go from there towards assets. This is the epitome of the evolution from web3 to web4. Web3 blockchains store assets, web4 timelines store people (who have assets and lifelines). Fortunately, once we accomplish this, a whole new world opens up.

This evolution from web3 to web4 is accomplished by mimicking and modeling the features of the universe, to move from our state machine from modeling <u>static assets</u> to modeling <u>alive actors</u> <u>in an alive universe</u>.

This is made feasible by encoding the rules of **energy** and **time** into our synchronized state machine model:

1. Time flows and redistributes energy.
2. Energy cannot be created or destroyed; it only moves around.
3. Energy gradually moves from less valuable entities and configurations in the universe towards more valuable entities.

Web4 is characterized by its **alive** nature and **sybil-resistance.**

In Society Protocol, individual actors—each with a proportional amount of energy–equal to their value to society at each point in time—are born, live, thrive (sometimes 😉), and die. Actors own accounts with true sybil-resistance and a persistent identity starting from birth and culminating in death. During their life they experience many events.

Individual actors engage in every conceivable activity we currently do in the world today, but it is all synchronized and coordinated globally to harmonize the desires of the individual with the needs of society as a whole.

Ownership of identity, data, and assets is returned back to the control of the individual.

The society has a constitution, laws, property, taxes, actors, organizations, religions, family trees, relationships, courts, and world parameters.

All these actions are transparently and verifiably synchronized globally at nearly the speed of light and stored our timeline as it ebbs and flows through time itself.

Society Protocol has developed a synchronized state that is able to fulfill all the essential functions of a network state by bringing the social layer on-chain and enabling sybil-resistance. It is a reimagining of societal coordination from first principles, using the blessings of technology afforded to us in the modern age.

**Web3 is dead. Web4 is alive.** Both literally and figuratively.

### Let’s revisit our comparison:

![](https://lex-img-p.s3.us-west-2.amazonaws.com/img/3e15a5d0-65cf-4854-a90c-1765b917e766-RackMultipart20250417-162-i00i2g.png)

## **Conclusion**

Everything we've explored reveals a fundamental truth: in current blockchain architectures, all metrics of decentralization can be falsified. Asset valuations, security mechanisms, governance structures, and even the underlying social coordination—all exist at the consent of invisible cabals. This isn't merely an occasional risk of bad actors, but an irreparable systematic reality embedded in the architecture of these systems.

As blockchain ecosystems continue to develop and gain mainstream adoption, we face a sobering future. Cabals will increasingly consolidate their power, systematically outcompeting traditional centralized institutions through regulatory arbitrage and opacity of operations. These cabals—operating sophisticated, distributed organizations with global reach—will gradually displace legacy financial cartels, not by delivering true decentralization, but by offering a valuable alternative that still concentrates power and wealth among a select few. The masses will continue to participate, lured by promises of decentralization and financial inclusion, while unknowingly strengthening very similar power structures to the ones they sought to escape.

Society Protocol aims to accomplish a fundamental reimagining of our approach to digital coordination, which is the only way to disrupt this inevitable trajectory.

Society Protocol disrupts this trajectory by bringing the social layer on-chain, creating genuine transparency around the very elements that cabals exploit. By establishing persistent, verifiable identities with real reputational stakes and immutable history, we transform the fundamental architecture of digital coordination—not through incremental improvement, but through a paradigm shift that fulfills the original promise of decentralization web3 can never achieve. This evolution from blockchains web3 vision to web4 with Society Protocol represents a transformative approach to human coordination: one that enables genuine decentralization through visible, sovereign digital citizens, each with persistent reputations and meaningful state. By implementing true sybil-resistance and modeling the natural laws of time and energy, we create systems where digital identities have consequence, actions require real energy, history is verifiable, and trust emerges without centralized control. The future of human coordination isn't in static assets controlled by invisible cabals—it's in living systems where the social layer itself becomes the foundation.

---
### Bibliography
1. Vitalik Buterin. (2022, March 14). _How do trusted setups work?_ [https://vitalik.eth.limo/general/2022/03/14/trustedsetup.html](https://vitalik.eth.limo/general/2022/03/14/trustedsetup.html)
2. Qureshi, H. (2019, October 31). _Ethereum is now unforkable, thanks to DeFi_. Haseeb Qureshi. [https://haseebq.com/ethereum-is-now-unforkable-thanks-to-defi/](https://haseebq.com/ethereum-is-now-unforkable-thanks-to-defi/)
 
### Footnotes
[^1]: For example, blockchain networks often claim to provide censorship resistance and credible neutrality. If examined in more detail, these features are completely dependent on who the imperceptible factors of who owns the assets and is running the network nodes. What are their beliefs and tendencies?
[^2]: This doesn’t necessarily include assets under control of that social layer i.e. in smart contracts. For example, assets locked inside a lending vault of a protocol that has vacated the blockchain network would remain there (assuming no governance changes), but the protocol governance token would become worthless (abandoned). This may or may not break the smart contracts.
[^3]: These groups do not necessarily have to preserve your assets when they switch, those are political and reputational consideration.
[^4]: It’s not going to happen, Society Protocol will absorb this entire industry.
[^5]: It’s interesting to note, these cabal groups can _feel each other_. They aren’t blindly competing for control of the global asset industry, identifying their potential rivals is <u>vital to them</u>. Even if it seems like each cabal is invisible, and should remain invisible to each other, _they can sense each other_. The largest Bitcoin miners know exactly who the _others_ are and keep a close eye on the power of potential rivals. The battle for the king of synchronized states is like Game of Thrones (the weaker ones die/implode and the stronger ones grow stronger).