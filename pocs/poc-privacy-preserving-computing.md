# POC Proposal: Privacy Preserving Computing

**Group:** `Proof of Concept (POC)`

**POC Category:** `core: trusted computation framework`


# Project Description
Itheum is a decentralised data brokerage. It's a cross-chain "Data DEX" that allows users to trade personal data securely on-chain (works on EVM chains). Itheum also allows for the storage of highly secure sensitive data within "Data Vaults" and we have a feature called the "Trusted Computation Framework" that brings the compute-to-the-data via privacy-preserving tech (like Secure Multi-Party Computation, Homomorphic Encryption and Zero-Knowledge Proofs). Itheum's other core features (peer-to-peer data trade, data NFTs, data coalitions DAOs) are gaining some traction (we were recently a winner at the moralis blockchain hackathon sponsored by polygon, elrod etc) but we want to also explore our options in the privacy-preserving compute space.

Itheum also has a deep integration with a web2 platform toolkit that enables the building of "data collection and analytics apps" - anyone can use this toolkit to build user data collection tools with built in outcome-oriented analytics. This product is already in the market and powers products like OKPulse (https://okpulse.life) and Red Heart Challege (https://itheum.com/redheartchallenge). The aim of this product is to democratise data collection and analytics technology and to increase the quality of high quality, outcome oriented personal data.

The data from these apps can then be "claimed" by the data creators in our Data DEX (https://datadex.itheum.com) and then traded using our decentralised tools. (watch a demo here - https://www.youtube.com/watch?v=63BE4plzDzw)

## We are proposing a `health industry use-case` as follows:

![Itheum Data DEX](https://raw.githubusercontent.com/Itheum/devgrants/rebrand/img/poc-privacy-preserving-tech.png)

As part of this Proof of Concept (POC) we'd like to demonstrate the privacy-preserving layer of our platform. In Itheum; this option is handled by the "Trusted Computation Framework" and enables sensitive data from the "data collection and analytics apps" to be sold to buyers without exposing the identity of both the buyer and seller. So a seller should be able to share a "sample of sensitive data" and the buyer should be able to share a "sample algorithm" with their "expected result quality" and the trusted computation layer should mediate the execution of the compute. It should provide back the data quality score and the guarantee the buyer is using the data as per algorithm definition (i.e. the terms of the use are as per agreed on). This enables for the trade to happen via privacy preserving principles and without any intermediaries.

## How it works end-to-end:
- We source and work with a "Research Partner" - see below section `Sourcing a "Research Partner"`
- We work with the "Research Partner" to highlight the `type on input data that will be available` and then formulate the `type of algorithm` that will need to run on it to get desired results. The expected `data quality threshold and algorithm output` will also be agreed upon.
- We work together to identify a large POC user-base (i.e. Data Creators) that will provide the data.
- Itheum will launch a new 'Data Collection and Analytics' app build upon the existing `Red Heart Challenge` app/program foundation (there will be public onboarding link for this app. e.g. https://itheum.com/redheartchallenge)
- Our POC users (Data Creators) will be invited to participate in the `Red Heart Challenge` program.
- Our POC users (Data Creators) will use the `Itheum Data DEX` to link their web3 accounts to the core `Red Heart Challenge` program.
- The `Itheum Data DEX` will ingest all the personal data and make it available for web3 trade.
- The user will use the `Personal Data Vault` to add sensitive demographic details about themselves. What exactly is required will be identified by our "Research Partner". Itheum's `Personal Data Vault` uses per-user encryption to protect the data and only unlock after consent is given to share.
- The user can now join the `Privacy Preserving Cardiovascular Research` Data Coalition. In the Itheum platform; `Data Coalitions` enabled for bulk sale of datasets that are structured and similar - hence, increasing the value of the data.
- The `Research partner` joins the Data DEX and subscribes to the above Data Coalition and specifies their `expected data quality threshold, algorithm sample and expected algorithm output threshold`
- The payment for the data and `Trusted Computation Framework` is paid in Itheum's utility token.
- A `job` is then created within the `Trusted Computation Framework` that details the work that needs to be done.
- for `Phase 1` this job is done in our `trusted sandbox` (see below).
- for `Phase 2` this job is sent to the `trusted network of nodes` who will coordinate the work and report back the results and close off the trade between buyer and seller.

## Deliverables
### Phase 1
- Create a `trusted sandbox` where we can input data samples from the `Red Heart Challenge` app and also input some sample algorithms from buyers and calculate the results
- The sandbox app will form the basis of the node software for phase 2 below

### Phase 2
- Build node software client based on the `trusted sandbox` design as above
- Create a `trusted network of nodes` that runs the client and operates under a consensus system that offer privacy preserving compute on demand to the Itheum platform
- These nodes will form the foundation of the `Trusted Computation Framework`

## Expectations / Terms
- Itheum is looking for a partner who can offer the `privacy preserving tech` as software or as-a-service
- Itheum is looking for development assistance from the company who can provide the `privacy preserving tech` (we can form a co-design/dev team)
- Itheum and the partner can form an official JV to explore the opportunity and share benefits of the outcome together

## Sourcing a "Research Partner" 
Itheum would require assistance from the partner to locate one or more research-partners who will be interested in "playing the role of the buyer" of the dataset generated via the above pipeline. This partner can be a caridiovascular health research institure, drug researcher, general data scienetist or anyone else who can provide acedemic validation that the outcome from our proof-of-concept provided value that otherwise is hard to obtain from current software or tools (non-blockchain based)

# Additional Information

- Please reach out to us on Discord if you would like to participate in this POC - https://discord.gg/y77P9gKF27 - we can deep dive into the tech design proposal for phase 1 and 2 together
