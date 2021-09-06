# POC Proposal: Privacy Preserving Computing

**Gooup:** `Proof of Concept (POC)`

**POC Category:** `core: trusted computation framework`


# Project Description
Itheum is a decentralised data brokerage. It's a cross-chain "Data DEX" that allows users to trade personal data securely on-chain (works on EVM chains). Itheum also allows for the storage of highly secure sensitive data within "Data Vaults" and we have a feature called the "Trusted Computation Framework" that brings the compute-to-the-data via privacy-preserving tech (like Secure Multi-Party Computation, Homomorphic Encryption and Zero-Knowledge Proofs). Itheum's other core features (peer-to-peer data trade, data NFTs, data coalitions DAOs) are gaining some traction (we were recently a winner at the moralis blockchain hackathon sponsored by polygon, elrod etc) but we want to also explore our options in the privacy-preserving compute space.

Itheum also has a deep integration with a web2 platform toolkit that enables the building of "data collection and analytics apps" - anyone can use this toolkit to build user data collection tools with built in outcome-oriented analytics. This product is already in the market and powers products like OKPulse (https://okPulse.life) and Red Heart Challege (https://itheum.com/redheartchallenge). The aim of this product is to democratise data collection and analytics technology and to increase the quality of high quality, outcome oriented personal data.

The data from these apps can then be "claimed" by the data creators in our Data DEX (https://datadex.itheum.com) and then traded using our decentralised tools. (watch a demo here - https://www.youtube.com/watch?v=63BE4plzDzw)

We are proposing a `health industry use-case` as follows:
![Itheum Data DEX](https://raw.githubusercontent.com/Itheum/devgrants/rebrand/img/poc-privacy-preserving-tech.png)

As part of this Proof of Concept (POC) we'd like to demonstrate the privacy-preserving layer of our platform. In Itheum; this option is handled by the "Trusted Computation Framework" and enables sensitive data from the "data collection and analytics apps" to be sold to buyers without exposing the identity of both the buyer and seller. So a seller should be able to share a "sample of sensitive data" and the buyer should be able to share a "sample algorithm" with their "expected result quality" and the trusted computation layer should mediate the execution of the compute. It should provide back the data quality score and the guarantee the buyer is using the data as per algorithm definition (i.e. the terms of the use are as per agreed on). This enables for the trade to happen via privacy preserving principles and without any intermediaries.

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

# Additional Information

- Please reach out to us on Discord if you would like to participate in this POC - https://discord.gg/y77P9gKF27 - we can deep dive into the tech design proposal for phase 1 and 2 together
