# POC Proposal: Multisig Protected Data Coalition Fund Pool

**Group:** `Proof of Concept (POC)`

**POC Category:** `core: data coalition `


# Project Description
Itheum is a decentralised data brokerage. It's a cross-chain "Data DEX" that allows users to trade personal data securely on-chain (works on EVM chains). `Data Coalitions` our one of the key features of the Itheum Platform and is a `DAO based entity that allows for the bulk-sale of personal data. Itheum's DAO designs were a **finalist in the Global DAOHack competition** and we presented our designs live in their final [YouTube pitch session](https://youtu.be/vjri1eD7dPE?t=2718).

Our current state of the DAO designs do have some flaws that we would like to address as part of the POC proposal. We detail the flaws and the recommended solution below.

## Problem:
- Data Coalition (DC) DAOs can have multiple board members (n) - which is decided when a new DC is created
- New members have to Stake utility tokens to join as a "Board Member"
- The "Chair" (Creator of the DC) also has to stake a lot of utility token
- Regular "Members" can then join the DC and contribute their data, the can also "stake and contribute" to show their commitment to good data quality
- Regular users of the Itheum platform can also "stake" on the DCs they like (to flag support for the DC and it's data quality)
- All the above staked / bonded utility tokens go into a common pool called the "DC Fund Pool"
- The DC Fund Pool is used for arbitration and dispute resolution in contentious sales of data
- Based on current design: the DC Fund Pool funds are controlled by the "Chair" - `THIS IS A PROBLEM as it's centralised`

## We are proposing `multi-sig protection for Data Coalition fund pools` as follows:

![Itheum Data DEX](https://raw.githubusercontent.com/Itheum/devgrants/rebrand/img/poc-multisig-datacoalition-fund-pool-new.png)

As part of this Proof of Concept (POC) we'd like to demonstrate how Multisig technology can make the Data Coalition Fund pool more robust and less prone to centralised influence and attacks. Our proposed solution is:

- The DC Fund Pool is a GnosisSafe (or a similar Multisig tech)
- And the "Board Member" are the safe "owners"
- For any transaction to go out - we will need **all owners to sign and agree**
- The integration with the Multisig tech should be seamless and ideally via the Itheum smart contracts (not front-end APIs etc)

## How it works end-to-end:
This has been detailed above in the `Problem` and `We are proposing` sections.

In addition to this:
- After the DC Fund Pool is protected via the Multisig safe, we will simulate a workflow to pay out a disgruntled buyer (contentious sale scenario) from the fund pool. This process will need the board members (safe owners) to agree and release the funds.

## Deliverables
### Phase 1
- Integrate the GnosisSafe (or a similar Multisig tech) into the Data Coalition workflow
- Satisfy the workflow described above in the `How it works end-to-end` section
- UX should be Seamlessly and not clunky

## Expectations / Terms
- Itheum is looking for a multi-sig technology partner to integrate with
- Itheum is looking for development support via Grants to help support the development efforts and adopt existing tools, platforms and technologies

## Sourcing a "Research Partner" 
Academic validation is not needed for this POC as it's a pure technical challenge.

# Additional Information

- Please reach out to us on Discord if you would like to participate in this POC - https://discord.gg/y77P9gKF27 - we can deep dive into the tech design proposal
