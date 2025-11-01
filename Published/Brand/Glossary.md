---
created: 2025-08-17T20:21
updated: 2025-10-31T12:28
---
# Concepts

Society Protocol terminology consists of main categories: <u>time</u> and <u>state</u>. 
1. **Time** pertains to everything with the tracking of passage of states over time, it conceptually contains: the Timeline, Timeslots, Timestamps, Time Interval (TI), and Timelapse. 
2. **state** pertains to the status of information within the system at various points in time. It conceptually contains: state, state slice, state sphere, public state, semi-private state, private state, state transition function (STF), and state that binds (STB). 

Timeline is the highest informational architectural structure, it contains the totality of all the states stored in the protocol throughout its history. Timeslot is the second tier informational architecture structure, it contains the state stored in the protocol at a snapshot on the Timeline. Events are the third tier informational architecture structure, each Timeslot contains multiple Events, which alter the state of the protocol.
- Blockchain translations: Timeline = blockchain, Timeslot = block, Events = transactions.
- If the Timeline is our calendar, the Timeslot is our clock (it contains the state, like a clock contains the current time).

Society Protocol terminology is meant to be used as proper nouns, to distinguish from the common definitions, i.e. Energy (Society Protocol Energy) vs energy (common noun). 
- The exception to this rule is `state`  terminology.
    - In the case of `state` terminology, other words included in the terminology should be capitalized or non-capitalized in the same manner as the capitalization of `state`. If the `state` is lowercase, do not capitalize other parts of the term.
# Terminology

## Time
- **Timeline:** The Timeline is the mapping of our synchronized state as it flows through time. It is synonymous with *blockchain* in Web3 terminology.
    - The Timeline can also be considered as the lifeline of the Society Protocol instance.
- **Timeslot (Time):** signifies a specific “time” on the Timeline.
    - Can alternatively be called *the Time* for shorthand.
    - The Timeline synchronizes the Society Protocol instance into one concrete state at each Timeslot.
    - Synonymous with *blocks* in a blockchain.
    - Include past Timeslot(s), current Timeslot, and future Timeslot(s).
    - **Genesis Time**: The first Timeslot in a Society Protocol instance. 
- **Time Interval (TI):** The empty space between Timeslots (when nothing occurs in the protocol).
- **Timestamp:** The cryptographic hash signature at each Timeslot.
- **Timelapse:** An array that encompasses a series of Timeslots.
    - Starting from Timeslot(start) and ending at Timeslot(end).

## State
- **State** (uppercase): The tribe, kingdom, or nation bound together by their shared state.

## state
- **state** (lowercase): Society's current condition or status—the collective memory and context that forms our shared reality.
    - **public state**: The public record, accessible to everyone, which the State propagates and uses to keep track of its current state.
    - **semi-private state**: The non-public shared context within subgroups, such as: families, friends, or organizations.
    - **private state**: An individual's current condition or status—the internal record unique to each person.
- **state sphere:** The hypersphere (4-dimensional sphere) contains the full state of the Society Protocol instance at any point in time.
    - Can alternatively be called the *state hypersphere* for a more formal representation.
- **state slice:** taking a subset of the state (not encompassing the whole state).
- **state transition function (STF):** The STF explains the ruleset of how each synchronized state updates its state between time intervals.
- **state that binds (STB):** Refers to  the state which binds our realities together and forms a shared reality (which is reached through a consensus). The STB phenomenon gravitationally pulls people together into a singular context, it has an energetic power and gravitational pull to it.
    - The gravitational pull and power of a STB (*expands)* and (*contracts)* based on the strength of the shared reality.
        - The Timeline is a “lifeline”. The Timeline grows (expands) and shrinks (contracts) in power based on the strength of the STB.
        - The state sphere element always contains the same 100% of Energy, but grows more vibrant with more activity happening inside the container.
    - Can alternatively be referred to as *shared reality.*
    - This force is responsible for both mass synchronization and mass psychosis.

### (S)synchronized (S)states
- **synchronized states:** Are protocols which synchronize a state for a certain social layer. There are two distinct things we talk about when discussing synchronized states.
    1. **synchronized states** (lowercase): can synchronize a state for a community, binding them to a shared reality, but not fulfilling all the essential functions to bind a State. 
        - Clocks, Bitcoin, Web3, and CBDCs are synchronized states.
    2. **Synchronized States** (uppercase): can synchronize a community, binding them to a shared reality, and fulfill all the essential functions to bind a State.
        - Society Protocol is a Synchronized State
        - Synchronized State and Synchronized Network State can be used interchangeably.

## Energy
- **Energy:** Is the base value system of Society Protocol instances.
    - Energy is zero-sum, it cannot be created or destroyed, it can only be transferred between different Actors and Organizations.
    - Energy can always be calculated as a percentage of the total Energy.
- **Energy Reserve**: The unallocated Energy of an Actor is stored in the Energy Reserve. 

## The Individual: Actors, Accounts, and Individuals
- **Actors & Accounts:** Actors control accounts.
    - Individual Actors, Sovereign Actors, or just Actors?
    - We will have both human and non-human Actors, should we delinianate further?
    - **Genesis Actors**: Actors who are alive at the Genesis Time of a Society Protocol instance. 
- **Lifeline**: Actors have a Lifeline, which is equal to the Timelapse between their Birth and Death Events.
- **Activity Score:** Each account has an Activity Score which is accumulated through activity, by performing Events at Levels and decays over time to calculate their “aliveness” in the protocol.
- **Programmable Will**: Automatically goes into effect upon the Death Event of an Actor to determine the lineage for ownership of their Property. 

## Events
- **Event:**  An event is an action which occurs inside the protocol, including: activity at one of the levels, energy transfers, birth & death events.
    - Includes: past event(s) and current event(s)
    - Synonymous with transactions in blockchain terminology. 
- **Historical events:** Historical events are an amalgamation of Events forming a larger historical picture.
- **Flashbacks**: The act of looking at events in the past in the Timeline.

## Protocol Artifacts
- **Constitution**: The Constitution initiates each Society Protocol instance with a certain ruleset, which can include both objective and subjective portions. The Laws in the constitution are the initial Laws of the protocol instance and can limit the power of Governance. 
- **Laws**: The legal structure of the protocol instance. 
- **Courts**: Make decisions about disputes of Actors and Organizations in the protocol instance.
- **Parameters**: Contain variables which control the "physics" of the protocol instance. 

## Levels
Levels are how instances of Society Protocol implement the redistribution of Energy. Each Level aims to combine individual interests with the societal interest to improve coordination abilities. 

1. **Parenting**: 
    - This Level forms Family Trees
        - **Parent**: The Actor issuing the invite to the system. Parents can introduce Children to their society, at a temporary cost to themselves, which can gradually reap rewards if those Children survive and are successful in the instance.
        - **Child**: The Actor receiving the invite to the system. Children are members of the instance, invited by the Parent, and can be dependent on the Parent, up to a certain time, during their infancy while they reach adulthood and can repay the parent.
        - **Birth Event**: This is a special Event in the protocol where a new Actor enters the system and begins their Lifeline. 
        - **Family Tree**: This explicit structure forms automatically in the protocol based off the Parenting level. 
2. **Hunting**
	- **Hunter:** Each Timeslot, one or multiple Hunters are selected to input Events into the protocol, and be rewarded with the Energy of the Hunted parties.
	- **Hunted:** Each Timeslot, one or multiple parties are chosen to be Hunted in the protocol in a probabilistic lottery in which their chances to win are based off their Activity Score.
	- **Hunt:**  Each Timeslot, there is a Hunt in which the Energy of the Hunted parties gets redistributed to the Hunter(s).
3. **Property**
    - Includes physical infrastructure such as factories and digital infrastructure such as smart-contract exchanges
    - Can alternatively be called *Programmable Property* or *Property Objects*, or *Objects*.
4. **Curation**
	- **Curator:** The Actor or Organization who is doing the curating. I.E. either creating a Curation Container or minting a Curation Slot. 
	- **Curated:** The Actor, Property, or Organization which is being analyzed.
	- **Curation Container:** A container filled with subjective information which is attached to the Curated and forms the root for a chain of Curation Slots. 
	- **Perspective:** The limitation list of the Actors and Organizations who are allowed to participate in this Curation Container. 
	- **Curation Unit Price (CUP):** The price to participate in a Curation Container and mint a single Curation Slot.
	- **Curation Slot:** An NFT received for participating in a Curation Container which collects royalties from other Curation Slots which are minted afterwards.
5. **Governance**: Has the ability to make changes to the Laws, Courts, Parameters, Levels, and Constitution of a Society Protocol instance.
	- **Governance Domains**: The five different areas of governance decisions in Society Protocol: Constitution, Protocol Parameters, Laws, Courts, and Disputes.
	- **Governors**: The people participating in the Governance of Society Protocol. 
	- **Distributed Courts (dCourts)**: An incentivized court system to make governance decisions which exists at the Governance Level. 
	- **Jury Pool**: The Actors and Organizations which participate in dCourts.
	- **Jury**: The Actors and Organizations which participate in dCourts and are selected to make a decision.
	- **Juror**: A single Individual Actor or Organization who is participating in dCourts.
	- **Futarchy**: A system of group decision making where prediction markets decide on what decision to make based on an optimization metric.
	- **Seers**: Actors and Organizations participating in Futarchy.
6. **Organizations**
    - This Level includes two types of Organizations:
        - **Distributed Corporations (dCorps)**
        - **Cultural Agreements (Cultures)**
            - Can alternatively be called _Distributed Cultures (dCultures, dCults)_.
7. **Communication**
    - Includes different types of communication at different tiers of privacy.
8. **Farming**
    - This Level is about incentivizing the storing of the state generated in a Society Protocol instance.
    - **Farmer:** The entity allocating their Energy to the Farming Level.  
9. **Portal**

## Synchronization & Coordination
- **4-Dimensional Synchronization** – 4D synchronization is a lossless method of synchronization obtained by sharing a duplicated computer program which synchronizes its state on 4 dimensions.
	- Shortform: 4D Sync
- **Web4** – Refers to a synchronized state which synchronizes a shared reality on 4-Dimensions. Enabling: read-write-own-coordinate. 
- **Byzantine Generals Problem** – The [Byzantine Generals Problem](https://bitcoinmagazine.com/glossary/what-is-the-byzantine-generals-problem) is a theoretical scenario in distributed computing that illustrates the challenge of achieving consensus among multiple parties when some may be unreliable or malicious. 
- **Automated Trust** 🤝 - The ability to automate trust between actors in the system algorithmically due to actors being objects in the system via cryptography and verifiable immutable history. 

## Supplementary Glossary
- **blockchain ledgers –** A blockchain is a decentralized, distributed digital ledger that records transactions across a network of computers in a secure, transparent, and tamper-resistant way.
- **CRUD -** CRUD is a computer science acronym which stands for **Create, Read, Update, Delete**. It refers to the four basic operations for managing state. 
- **lossy communication –** During lossy communication, information (state) is transmitted in a way that mutates, either due to a difference of perception, duality, or compression.   
- **lossless communication** – In lossless communication, information (state) is transmitted or stored without any loss of information, preserving the original content exactly. 
- **immutable** – This refers to blockchains ability to stop the shared reality from mutating. Immutability is not an absolute feature, and merely a narrative of verifiable useful information.  Nevertheless, it is a useful narrative to understand and reason about the mutability of state in this way. 
- **permissioned** – Permissioned refers to blockchains or synchronized states where the access to account creation and use is controlled by a specific group of entities. 
- **permissionless** – Permissionless refers to blockchains or synchronized states where account creation and access is not restricted and any entity can create an unlimited amount of accounts. 
- **bearer** – A bearer is a person who possesses a physical or digital document, token, or asset that grants them certain rights, typically without requiring additional proof of identity or ownership. The term is often used in financial and legal contexts to denote someone who "bears" or holds the item. 
- **bearer assets** – Assets where ownership is determined by possession. Whoever holds the asset (physically or digitally) is considered its owner, and no additional registration or proof of identity is needed. Examples include cash, certain cryptocurrencies, and bearer bonds.
- **Turing-complete** –  A system, programming language, or computational model is Turing complete if it can simulate a Turing machine, meaning it can compute any function that a Turing machine can, given enough time and resources. A Turing machine, as conceptualized by Alan Turing, is a theoretical device capable of solving any computable problem through a set of instructions. 
- **centralized exchange (CEX)** – A centralized exchange is a platform for trading assets (e.g., cryptocurrencies, stocks) operated by a central authority or company. The exchange acts as an intermediary, managing the trading process and holding users' funds.  
- **decentralized exchange (DEX)** – A decentralized exchange is a platform for trading assets that operates without a central authority, using blockchain technology and smart contracts to facilitate peer-to-peer transactions.
- **sybil attack** – A type of attack in a distributed system or network where a malicious actor creates multiple fake identities (or "Sybil nodes") to gain disproportionate control, influence, or power.
- **sybil resistance** – Sybil resistance refers to mechanisms designed to prevent or mitigate Sybil attacks in distributed systems, networks, or protocols. A Sybil attack occurs when a malicious actor creates multiple fake identities (or "Sybil nodes") to gain disproportionate influence, manipulate outcomes, or disrupt the system's integrity. Sybil resistance aims to ensure that a single entity cannot control or compromise the system by pretending to be many participants.
- **triple-entry accounting** – An advanced accounting system that extends the traditional double-entry bookkeeping method by introducing a third entry, typically recorded on a shared, immutable ledger.

---