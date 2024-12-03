---
description: Find relevant information and quick answers to your questions.
icon: comment-question
---

# FAQ

<details>

<summary>What does "Owner Wallet Analysis" mean?</summary>

Our scanner checks several details about the contract deployer wallets, such as the balance, from where it was funded, and the oldest transaction on the wallet. Moreover, we provide risk analysis in the following way: the bot tracks past deployments connected to this wallet, scans if they were rugged or not, and then we put them into 3 categories: distance 0 (number of contracts the wallet directly deployed and rugged), distance 1 (number of rugging wallets that funded the current deployer wallet), distance 2+ (number of rugs connected to the deployer that are at least 2 hops away).

</details>

<details>

<summary>What does "Checksum" mean?</summary>

In cryptography, a checksum is a value derived from the digital representation of data in the form of a hash. The purpose of a checksum in our scanner is to verify the integrity of the data and detect similarities/differences. If two checksums are matching, that means that the functions in the smart contracts are 100% the same (but the integers, such as the tax, etc., can differ). Ergo, it is a reused contract or "fork". Even a small change in the data results in a significantly different checksum. It is a great way to "predict" by the contract's history if it is prone to rugs or if it is a relatively safe solution. Take care. Even the safest contract can be rugged!

</details>

<details>

<summary>What does "SUS code detected, DYOR" mean?</summary>

In this case, our bot has spotted an anomaly in the tokenomics (for example, pre-loaded contract) or at least one function (for example, honeypot, delayed honeypot, no hardcoded limits, blacklist, etc.) that can be used for malicious practices. Proceed with caution and DYOR. Most of these tokens will end up getting rugged.

</details>

<details>

<summary>What does the "Safety Index" mean?</summary>

We have released our own scoring system grading ERC20 smart contract deployments by several metrics: historical similarities, tokenomics, code quality, suspicious activities, owner wallet analysis, and a lot more (we won't share the exact formula to avoid scammers taking advantage of it). We give a token a rating of up to 10 based on these details, assessing how safe a launch should be based on our data (10 being the best, 0 being a rug, almost certainly). Please note that this formula might be inaccurate sometimes, as it is an in-development/experimental estimation. Always DYOR!

</details>

