# Buterin-Proposed Constantinople Ethereum Feature Allegedly Introduces Attack Vector ...

###### 2019-02-13 10:02

Ethereum (ETH) co-founder Vitalik Buterin has proposed a new smart contract creation function dubbed “Create2.”

This function reportedly introduces a new attack vector to the platform, according to a post on the Ethereum developers forum Ethereum Magicians published on Feb. 8.

According to a Medium post by software developer Tim Cotten, the original create function creates a new contract at an address that is calculated (through a hash function) with the creator’s address and a random number (nonce) associated with it.

Create2, on the other hand, reportedly does the same, but with the difference that the contract is created at an address that can be determined beforehand by different parties.

In the GitHub page dedicated to this Ethereum Improvement Proposal (EIP), EIP-1014, the motivation for the new function is described as the ability to permit an interaction with a contract that does not exist on the blockchain yet.

According to him, Create2 implies that smart contracts will be able to change their address after being deployed.

Jason Carver, senior staff engineer at the Ethereum Foundation, explained that he thinks that it will be possible to use Create2 to replace a self-destructed contract with a new one.

[Original source](https://cointelegraph.com/news/buterin-proposed-constantinople-ethereum-feature-allegedly-introduces-attack-vector)

![stats](https://c.statcounter.com/11760860/0/a89fa40b/1/ "stats")