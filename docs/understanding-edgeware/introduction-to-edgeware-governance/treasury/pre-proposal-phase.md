# Treasury Proposal Guide

### Intro

Once you have an idea that might be appropriate for funding from the Edgeware Treasury, you can complete several steps to test the public interest, convey your argument, and then submit your formal treasury proposal.  This guide is written as a recommendation both to proposers and decision-makers, and will track best practices over time as they emerge.  

Similar to traditional RFPs \(request for proposals\) that governments use to solicit bids for work, treasury spends optimize the productive value of the EDG and seek to extract maximum work for their recipients. Proposers should be prepared to defend their position or experience competitive bids for the same or similar work. 

### Technical Process of a Treasury Spend

1. Pre-Proposal Stage - Planning, writing, advocacy, outreach.
2. Treasury Spend Proposed
3. Council either adopts or refuses the proposal.
4. If approved, it enters a queue within a budget period of 24 days. 
   1. The treasury attempts to fulfill as many spends in the queue within this time period.
   2. At the end of a budget period, the remaining treasury balance is subject to a small percentage burn. This incentivizes the usage of funds and creates deflation through the destruction of EDG.
5. If refused, the treasury proposal remains able to be accepted until the end of the 24 day period, then it is removed from the consideration table but can be resubmitted.

### Plausible Project Concepts 

Projects that serve the broader Edgeware ecosystem are much more likely to succeed than other kinds of efforts. 

* **Open source** projects; some closed source may be successful depending on the case.
* Tooling and Developer experience
* User Experience, wallets, DEXs, clients
* Infrastructure
* Monitoring, auditing, security operations
* Cross-chain collaborations
* Events, meetups, hackathons
* Primitive Development
* Bridges and Interoperability
* Governance Improvements
* Cryptography
* Core Development
* Identity projects
* Smart Contract resources
* Validation resources
* Brand and marketing campaigns
* Community organization efforts

This list is not exhaustive, but it gives you a sense of what sorts of things are good propositions.

### Proposal Description Document

The first step is to describe the proposal in full to the community.  A great place to start is a single document that contains all the following information. Once the document is ready, create the on-chain spend in the next step, then share the document after.

1. Date of Proposal
2. Who is proposing? 
   1. What is their motivation?
   2. Do they have any conflicts of interest?
   3. To who do these payments go?
      1. For building, who will be handling what? 
      2. What is their background and expertise? Describe the whole team.
3. What is the historical context of this proposal?
   1. What previous actions does this proposal relate to?
   2. Does it have any impacts on future actions to note?
4. Clear, short Problem Statement and Proposed Solution 
   1. Evidence for that Solution 
   2. Who does this solution help?
5. Financial Details for all Proposed Transfers
   1. Amount/s requested
   2. Financial timeline  - when are installments due?
   3. What are the Addresses of the fund recipients?
   4. Who will be managing the funds, how can we contact them?
   5. How will the manager of the funds report on status proactively? Where we can follow progress and ask questions?
6. License \(if applicable\)



### Propose The Spend On-Chain

When you propose a treasury spend,  **a deposit totaling 5% of the proposed spend amount, with a minimum of 1000 EDG is required.This deposit will be slashed if the proposal is rejected,** and returned if the proposal was accepted.

One way to create the proposal is to use the Polkadot JS Apps [website](https://polkadot.js.org/apps). From the website, use either the [extrinsics tab](https://polkadot.js.org/apps/#/extrinsics) and select the Treasury pallet, then `proposeSpend` and enter the desired amount and recipient, **or** use the [Treasury tab](https://polkadot.js.org/apps/#/treasury) and its dedicated Submit Proposal button:

![](../../../.gitbook/assets/image%20%289%29.png)

The system will automatically take the required deposit, picking the **higher** of the following two values: 1000 EDG or 5% of the requested amount. If the user cannot pay the deposit, an error will be returned and the proposal creation will fail.

![A proposal ready for the council to consider](../../../.gitbook/assets/image%20%288%29.png)

Once created, your proposal will become visible in the Treasury screen and the council can start voting on it.

**Note the on-chain \# of your treasury proposal-** shown as a large number on the left of the row \(11 in the image above\), you'll want it for the next step. 

Now the council can take action, either turning it into a motion to approve or a motion to reject. 51% or more of the council must agree to take an action on any treasury spend.

{% hint style="info" %}
**Parameter Note:**  The _Treasury Spend Deposit_ is 5% of the proposed spend action, with a minimum of 1000 EDG. _Treasury Spends_ require 51% of the council to agree.
{% endhint %}

### Speak with the Community

Because the formal spend proposal lacks metadata for efficiency, sharing the details about the proposal off-chain is essential. We recommend using [Commonwealth.im/Edgeware](https://Commonwealth.im/edgeware) and the community channels including telegram and discord.

* Post a discussion thread on Commonwealth
* Tag the title and body with **EDG\_TP\_\#** where \# is the official number of your treasury proposal, found on block explorers or Polkadot UI. 
* Announce the thread in other channels like Telegram to encourage awareness and debate.

Tagging helps users understand what module is being activated and what threads connect to what actions. Expect questions, challenges, and other remarks.  This can begin before or after you create your formal treasury proposal on-chain, but you won't know the TP\# until then.
