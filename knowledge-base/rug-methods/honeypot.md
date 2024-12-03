---
description: Probably the most common rug method.
icon: honey-pot
---

# Honeypot

**How It Works**:

* In a honeypot, developers create a token with a smart contract that allows buying but blocks selling. Unsuspecting investors buy the token, only to find out they cannot sell it.
* The developers then dump their holdings, taking the liquidity and leaving investors stranded.
* Often, you'll find contracts where owners are generating high volume on purpose to imitate a hyped launch. They are able to "whitelist" these volume-generating wallets to sell so that it seems to outsiders that the contract is not configured for honeypotting new buyers.

**How to Spot It**:

* **Test Transactions**: Start with small transactions to test buying and selling the token. There are contract simulators integrated into many chart services like Dextools or Dexscreener, which help you with useful insights.
* **Smart Contract Analysis**: Check for restrictive code that limits sell functions or imposes unusually high sell fees.
