# Validators & Delegators



The ever-evolving crypto space has given rise to several blockchain types. Among other factors, a significant point of difference is how they verify actions.

A vital component of blockchain technology is its consensus algorithm. This mechanism allows users or machines to coordinate with one another safely and effectively.

The consensus algorithm is also crucial in securing the blockchain network from malicious intent. It ensures that all users or machines in the system agree on a single source of truth, even if some fail.&#x20;

The three most widely known consensus algorithms to date are Proof of Work (PoW), Proof of Stake (PoS), and Delegated Proof of Stake (DPoS).&#x20;

BitCanna's blockchain is built with Cosmos SDK and uses Tendermint's BFT consensus algorithm (DPoS). To understand how BitCanna operates, we’ve broken down key terminology and how different actions influence the network.

### Validators&#xD;

So-called Validators verify network transactions within the BitCanna blockchain.

Validators are network node operators that validate data transmitted in the blockchain. To take part in the blockchain, validators need to "[stake](staking.md)" a certain amount of chain-specific coins. In BitCanna's case, this is BCNA.&#x20;

This stake acts as collateral, keeping validators honest and active within the network. If validators decide to act in bad faith or fail to contribute, "[slashing](slashing.md)" can occur. Slashing is a disciplinary action that results in the loss of BCNA coins.

Often, blockchains set a maximum number of validators that can be active at the same time. Again, in the case of BitCanna, a maximum of 100 validators can be simultaneously active. You become one of the top 100 active validators according to the size of your stake—the amount of BCNA coins you hold (self-delegated coins and delegations from others). Note: delegated coins are not the property of the validator and can not be used by the validator other than governance.

These delegations also count as votes for a particular validator, although anyone holding BCNA coins is free to vote. While there can be more than 100 validators, these won't be actively validating blocks, and are referred to as inactive validators.&#x20;

Inactive validators serve as a backup should a validator fall out of the top 100. At a later stage, the number of active validators can increase or decrease via [governance](governance.md).&#x20;

### Bonded, Unbonding, and Unbonded&#xD;

A validator can operate in several states; namely,

#### Bonded&#xD;

A validator is actively taking part in signing blocks and therefore earns rewards. In this state, a validator can be slashed.

#### Unbonding&#xD;

A validator is not actively taking part in signing blocks, but can still be slashed for misconduct.&#x20;

#### Unbonded&#xD;

The validator is not actively signing blocks, can't be slashed, and does not earn rewards. Delegators can still delegate to an unbonded validator.

### Signing Block Chance&#xD;

Data that needs validation is held in a transaction block. The time it takes to handle a block (\~5.5 seconds) is referred to as "blocktime", with each block randomly assigned to one of the top 100 validators. Validating the block and writing it to the blockchain earns the selected validator a portion of BCNA coins.

However, the validator selection process isn't entirely random, with several variables taken into account.&#x20;

The total amount of a validator's self-delegated stake and any delegations results in "voting power". Validators with a larger investment in the BitCanna blockchain (stake) have a greater chance of being assigned blocks. However, they still need to take extra care of their uptime or risk slashing. Both the validator's self-delegated stake and any delegated stakes are vulnerable to slashing.&#x20;

#### Voting Power&#xD;

The greater the voting power, the more likely a validator is elected to sign blocks. As already stated, delegations correlate directly to voting power—for each delegation assigned, the validator's voting power increases. Voting power also allows a validator to have a say in governance proposals. More voting powers mean a bigger influence on updates and future blockchain development.

Being a validator takes considerable knowledge, with a steep learning curve and specific software needed to keep the blockchain updated and stable. Unfortunately, not every BitCanna user will be able to be a validator. For more information about becoming a validator within the BitCanna network, please visit the BitCanna Validator Hub.

### Delegators&#xD;

Anyone with BCNA coins can become a Delegator—all it takes is a few clicks within the BitCanna wallet. The act of allocating BCNA coins to a validator is called delegating and helps distribute voting power among validators. The entire concept of validators and delegators directly supports the decentralisation of the BitCanna blockchain.&#x20;

It's essential to understand that the top 100 validators aren't the only users controlling the BitCanna network. All other holders of BCNA coins can participate in the consensus by controlling validators with their delegations. It is of the utmost importance that a delegator picks validators wisely and withdraws their delegated stake if a validator acts in bad faith.&#x20;

By delegating, a delegator is voting for a particular validator, granting them voting power. Doing so means that the delegator's BCNA coins are temporarily assigned to that validator, increasing their voting power and their chance to be elected to sign blocks within the chain.&#x20;

In return, the delegator is awarded a share of the validator’s rewards. It's up to the validator to set their reward via commission ratios. But beware; a validator being slashed also has consequences for delegators—finding a trustworthy and reliable validator is paramount!

However, a validator does not hold or own the delegator's BCNA coins. Instead, they simply earn rewards when assigned BCNA coins. This means that a delegator can un-delegate or "unbond" their BCNA coins at any given time (keeping in mind the mandatory unbonding period of 14 days). After the unbonding period, the delegate's BCNA coins are unlocked and free to be moved or assigned elsewhere.



