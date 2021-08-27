# 1. Blockchain Fundamentals

## What is Blockchain?

### Definitions and Origins
* [Blockchain](https://en.wikipedia.org/wiki/Blockchain) -- " a growing list of records, called blocks, that are linked together using cryptography." 
* [History](https://www.blockchain-council.org/blockchain/a-detailed-history-of-blockchain-from-the-establishment-to-broad-adoption/) of [blockchain](https://101blockchains.com/history-of-blockchain-timeline/) -- Idea started in 1991
* Invented in 2008 by Satashi Nakamoto with the introduction of Bitcoin

### Types of distributed concensus
* [Distributed concensus](https://www.geeksforgeeks.org/distributed-consensus-in-distributed-systems/) -- "A procedure to reach a common agreement in a distributed or decentralized multi-agent platform. It is important for the message passing system."
* http://elaineshi.com/docs/blockchain-book.pdf
* https://computersciencewiki.org/index.php/Distributed_consensus

### Purposes and use cases
* https://consensys.net/blockchain-use-cases/

## What is a smart contract?
* https://www.ibm.com/topics/smart-contracts

### Introduction to Smart Contracts
* [Introduction to smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/)

### Smart Contract Use Cases and Platforms
* https://www.trustradius.com/smart-contracts
* https://insidebitcoins.com/news/5-top-crypto-smart-contract-platforms-august-2021

##  Keys, Wallets, and Cryptography

### Hashing Functions
* [Hash function](https://en.wikipedia.org/wiki/Hash_function) -- "is any function that can be used to map data of arbitrary size to fixed-size values"
* [Cryptographic hash function](https://en.wikipedia.org/wiki/Cryptographic_hash_function) -- "a mathematical algorithm that maps data of arbitrary size (often called the 'message') to a bit array of a fixed size (the 'hash value', 'hash', or 'message digest')"
* [Difference between a hash function and a cryptographic hash function](https://security.stackexchange.com/questions/11839/what-is-the-difference-between-a-hash-function-and-a-cryptographic-hash-function) -- TL;DR a hash function is a general term for a function that maps data of any size to fixed size where a cryptographic hash function has specific properties. These properties include:
  - Deterministic (same input will always produce same output)
  - Fast to compute it
  - Infeasible (almost impossible or completely impossible) to reverse the hash
  - Infeasible to get collisions
  - Small change to an input (ex. one bit difference) will give a completely different hash output that cannot be anywhere near the original input

### Types of Cryptography
* [SHA-2](https://en.wikipedia.org/wiki/SHA-2), specifically SHA-256, is used extensively in blockchain (Bitcoin proof-of-work)

### Wallets
* [Cryptocurrency wallet](https://en.wikipedia.org/wiki/Cryptocurrency_wallet) -- "device, physical medium, program or a service which stores the public and/or private keys for cryptocurrency transactions."
* https://www.investopedia.com/terms/b/blockchain-wallet.asp

### Mnemonic Keys
* https://community.algorand.org/blog/understanding-mnemonic-keys-and-how-they-are-generated-on-the-algorand-blockchain/

## Consensus Mechanisms

### Proof of Work
* [Proof of Work](https://www.investopedia.com/terms/p/proof-work.asp) "describes a system that requires a not-insignificant but feasible amount of effort in order to deter frivolous or malicious uses of computing power, such as sending spam emails or launching denial of service attacks."
* https://www.ledger.com/academy/blockchain/what-is-proof-of-work

### Mining - The History and the Process
* https://blog.honeyminer.com/history-of-cryptocurrency-mining/
* https://www.investopedia.com/tech/how-does-bitcoin-mining-work/
* https://www.dummies.com/personal-finance/investing/what-is-cryptocurrency-mining/
* https://www.analyticsvidhya.com/blog/2021/05/how-to-mine-bitcoin-using-python-part-i/

### Proof of Stake
* [Proof of Stake](https://www.investopedia.com/terms/p/proof-stake-pos.asp) -- "a person can mine or validate block transactions according to how many coins they hold"
* https://www.coindesk.com/tech/2020/12/30/what-is-proof-of-stake/
* https://www.geeksforgeeks.org/proof-of-stake-pos-in-blockchain/
* https://mycoralhealth.medium.com/code-your-own-proof-of-stake-blockchain-in-go-610cd99aa658

### Lightning Network
* [Lightning Network](https://en.wikipedia.org/wiki/Lightning_Network) -- "a 'layer 2' payment protocol designed to be layered on top of a blockchain-based cryptocurrency such as bitcoin or litecoin."
* https://lightning.network/
* http://lightning.network/how-it-works/
* https://www.blockchain-council.org/blockchain/a-quick-guide-on-lightning-network/

## Blockchain Transactions

### Components of a Transaction
* https://coincentral.com/what-is-a-blockchain-transaction-anyway/
* https://rehack.com/featured/how-do-blockchain-transactions-work-and-what-can-they-do/
* https://decrypt.co/resources/blockchain-transactions

### Block Explorers

## Blockchain Components

### Bitcoin - API, Nodes, and Clients
* https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list
* https://101blockchains.com/blockchain-nodes/
* https://nodes.com/

### Ethereum Architecture
* https://en.wikipedia.org/wiki/Ethereum
* https://www.zastrin.com/courses/ethereum-primer/lessons/1-5

## Labs

### Lab 1.1: Create a HD Software Wallet
* https://medium.com/bitcraft/so-you-want-to-build-a-bitcoin-hd-wallet-part-1-8b27aa001ac3
* https://medium.com/coinmonks/bitcoin-hierarchical-deterministic-wallet-in-python-5947147e3eda

### Lab 1.2: Join a Blockchain Mining Pool
* https://thecleverprogrammer.com/2021/01/18/bitcoin-mining-with-python/
* https://medium.datadriveninvestor.com/building-a-blockchain-in-python-f194a26530fd

### Lab 1.3: Blockchain Transaction Analysis
* https://en.wikipedia.org/wiki/Blockchain_analysis
* https://medium.com/coinmonks/whats-blockchain-analysis-a-descriptive-guide-5d7e3476991d

### Lab 1.4: Use the Bitcoin-cli to Interact with an API
* https://www.kompulsa.com/bitcoin-cli-commands-and-api-methods/
* https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_calls_list
