---
description: Leveraging an additional layer of sending messages.
icon: hive
---

# On-Chain Alerts

Horus provides 2 different categories of on-chain messages sent from two independent wallets:

* **On-Chain Scam Alerts**: Sent from [scam-alert.horustools.eth](https://etherscan.io/address/0xd5123310eC65Bc7d3E70Ac57c284a3f73EA63ea5) ENS, this wallet alerts unsuspecting traders by sending a message to a tokens deployer before its imminent rug. This tool spots pre-loaded wallets and suspicious deployer wallets that have been active in previous scams, saving dozens of ETH for innocent people.
* **On-Chain Reversal Alerts**: Sent from [insider-activity.eth](https://etherscan.io/address/0xD54E31903C6c4Ee3E5Dd62db1b48253002F6D5F7) ENS, this wallet informs on-chain explorers by sending a message to a tokens deployer if that token is actually pumping after being signaled by the Reversal bot, directing attention to our tools.
