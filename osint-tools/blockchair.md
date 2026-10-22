---
description: >-
  Tool Description: A multi-blockchain search and analytics engine that allows
  you to examine cryptocurrency addresses, transactions, blocks, and token
  activity.
---

# Blockchair

| **Blockchair**   | **Quick Overview**                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://blockchair.com/](https://blockchair.com/)                                                                                                                                    |
| What it does     | Searches and analyses public blockchain data, including wallet addresses, transactions, blocks, tokens and transaction histories across multiple networks.                            |
| How to use it    | Search a wallet address, transaction hash or contract address, inspect balances and transactions, follow connected transactions then verify findings against the relevant blockchain. |
| Cost             | Partially Free.                                                                                                                                                                       |
| Account required | No for basic searches.                                                                                                                                                                |
| Cookies          | Matomo analytics cookies,, a Qrator-related anti-bot cookie, an application session cookie, and an XSRF-TOKEN cookie.                                                                 |
| Ownership        | Privately held company HQ’d in Dublin and headed up by Nikita Zhavoronkov.                                                                                                            |
| Use in Reporting | Cryptocurrency transaction tracing, wallet-history research, financial investigations, address screening and documenting on-chain activity.                                           |

### What does Blockchair do?

Blockchair is a blockchain search engine that brings data from multiple cryptocurrency networks into one interface. You can search addresses, transactions, blocks and token contracts, inspect transaction histories, and filter or sort records to investigate how cryptocurrency moves between addresses.

It also offers a REST API, downloadable datasets, charts, blockchain statistics and other tools for analysing blockchain activity. Its API supports SQL-like filtering, sorting and aggregation for more structured research.

**The lowdown:** It’s especially useful when an investigator has an initial wallet address, transaction hash or contract address and needs to examine the public transaction history around it.

### How to Use:

**1. Select the relevant blockchain, or enter a wallet address, transaction hash or contract address into the search field.**

<img src="../.gitbook/assets/unknown (741).png" alt="" height="156" width="602">

**2. Examine the returned information, including transaction history, balances, amounts, timestamps, fees and other chain-specific details. Identify relevant incoming and outgoing transactions and any addresses requiring further examination.**

If you’re using the block explorer, you can view transactions as below:

<img src="../.gitbook/assets/unknown (742).png" alt="" height="249" width="602">

**3. Follow relevant transaction links to build a basic picture of the flow of funds. Record transaction hashes, addresses, blockchain, timestamps and access dates, and corroborate important findings with additional blockchain explorers or specialist blockchain-analysis tools.**

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Public explorer features are free. API access has a free testing allowance and paid options for higher-volume use.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

No for ordinary explorer searches. API keys or subscriptions may be required for ongoing or higher-volume API use.

### Cookies:&#x20;

Testing identified Matomo analytics cookies (\_pk\_id.1.641f and \_pk\_ses.1.641f) for visitor and session measurement, a Qrator-related anti-bot cookie (qrator\_jsid2), an application session cookie (whiskey\_4\_session) and an XSRF-TOKEN cookie for request-forgery protection.

### Use in Reporting

Blockchair can be useful for:

* Examining the transaction history and balances associated with a cryptocurrency address.
* Tracing incoming and outgoing transactions to identify possible transaction paths and counterparties.
* Recording transaction hashes, amounts, timestamps, fees and other publicly available on-chain details.
* Investigating potential cryptocurrency movements relevant to fraud, theft, scams, sanctions evasion or asset-recovery enquiries.
* Searching token contracts and examining activity on supported blockchain networks.
* Supporting financial research by providing structured data that can be filtered, exported or analysed through the API.
* Providing traceable blockchain records that can be independently verified and cited in reports.

Blockchair has also been explicitly recommended in [government guidance](https://www.ncmba.uscourts.gov/sites/ncmba/files/BA%20guidance%20re%20cryptocurrency%20investigations%202025-8-25.pdf). An August 2025 letter from the U.S. Bankruptcy Administrator for the Middle District of North Carolina advised trustees that Blockchair could be used to trace cryptocurrency transactions and review wallet balances and transaction histories when investigating potential cryptocurrency assets.&#x20;

| **Capabilities**                                                                                | **Limitations**                                                                                              |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Search wallet addresses, transactions, blocks and token contracts across supported blockchains. | Coverage and available data vary by blockchain. Some networks or assets may have incomplete historical data. |
| Examine balances, transaction histories, amounts, timestamps and fees.                          | Public blockchain records do not automatically reveal the real-world identity of an address owner.           |
| Follow transaction links to investigate flows of funds between addresses.                       | A transaction path alone does not establish intent, beneficial ownership or criminality.                     |
| Filter, sort and aggregate blockchain data through the explorer and API.                        | API use is subject to plan limits, rate limits and possible costs for higher-volume research.                |
| Provides charts, downloadable datasets and additional blockchain-analysis features.             | Some features are chain-specific and require technical knowledge to interpret correctly.                     |

### Summary

Blockchair fits primarily into the discovery, verification and analysis stages of the OSINT workflow, with its main value is making public blockchain data searchable and easier to examine across multiple networks.&#x20;

However, the platform should be treated as a blockchain discovery and analysis tool, not as proof of the real-world identity of a wallet owner. On-chain data can establish that a recorded transaction occurred, but connecting an address to a person or organisation generally requires independent evidence.

### Ownership

Privately held company HQ’d in Dublin and headed up by [Nikita Zhavoronkov.](https://www.crunchbase.com/person/nikita-zhavoronkov)

### Ethical Considerations

* Treat a wallet address as a pseudonymous identifier unless independent evidence connects it to a real person or organisation.
* Distinguish observed transactions from inferred relationships, motive or suspected wrongdoing.
* Verify significant findings using transaction hashes and additional sources, and preserve the chain, timestamps and source records.
* Check whether the chain exposes complete history for the relevant data type before drawing conclusions from missing transactions.
* Avoid publishing unnecessary wallet details that could expose a private individual's financial activity or create personal-security risk

### Related Tools:

* [Etherscan](etherscan.md)
* [Block Explorer](block-explorer.md)
* Solscan
* [Arkham Intelligence](arkham.md)

#### Sources

[https://blockchair.com/](https://blockchair.com/)&#x20;

[https://blockchair.com/about](https://blockchair.com/about)&#x20;

[https://blockchair.com/privacy](https://blockchair.com/privacy)&#x20;

[https://www.crunchbase.com/organization/blockchair](https://www.crunchbase.com/organization/blockchair)&#x20;

[https://www.crunchbase.com/person/nikita-zhavoronkov](https://www.crunchbase.com/person/nikita-zhavoronkov) [https://www.ncmba.uscourts.gov/sites/ncmba/files/BA%20guidance%20re%20cryptocurrency%20investigations%202025-8-25.pdf](https://www.ncmba.uscourts.gov/sites/ncmba/files/BA%20guidance%20re%20cryptocurrency%20investigations%202025-8-25.pdf)&#x20;
