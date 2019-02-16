# Vitalik Buterin Dismisses Rumors New Constantinople Feature Allows Attack Vector ...

###### 2019-02-16 09:02

Ethereum (ETH) co-founder Vitalik Buterin and other core devs have dismissed allegations that a new smart contract creation feature set to be released in the forthcoming Constantinople hard fork will have negative security implications.

The feature in question is called “Create2” — designated as Ethereum Improvement Proposal (EIP) EIP-1014 — and is intended to allow for interactions with a contract that does not yet exist on the blockchain — specifically, “addresses that do not exist yet on-chain but can be relied on to only possibly eventually contain code.”

Several ETH devs had voiced concerns that Create2 could introduce a potentially serious attack vector to the network, given the implication that smart contracts could purportedly be coded to change their address after being deployed.

In a discussion of this and other comments, dev Jeff Coleman underscored that “one of the things that is counter-intuitive about Create2 is that theoretically redeployments can change the contract byte code, because the address is only a commitment to the init code.

Coleman stressed that those who are looking to audit others’ code need to look out for potentially “weird phenomena \[...\] especially if you combine Create2 with Create1, because the latter has a really weak assumption around address identity whatever the nonce is.”

So if we get to the place where Create2 is standard, get rid of self destruct entirely \[...\] we could throw out this idea of a contract nonce.”

Like Coleman, Vitalik Buterin discussed Create2 in regard to a longer-term roadmap, saying:

“The one thing we need to keep in mind is more for the future, when thinking about rents and deletion; that’s a way that can lead to contracts being in a state to being not in a state without a self-destruct operation \[...\].

[Original source](https://cointelegraph.com/news/vitalik-buterin-dismisses-rumors-new-constantinople-feature-allows-attack-vector)

![stats](https://c.statcounter.com/11760860/0/a89fa40b/1/ "stats")