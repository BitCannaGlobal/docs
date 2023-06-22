# Slashing

Slashing is a disciplinary action against a [**validator**](validators-and-delegators.md#validators). This mechanism is built into delegated proof of stake blockchains to discourage validator misbehaviour and encourage them to play an active role in a chain's security and availability.&#x20;

### Misbehaviour&#xD;

Actions that could result in disciplinary slashing are predominantly: downtime and double signing.

One crucial factor in disciplinary action is uptime—the time a validator is available and actively taking part within the blockchain, signing blocks. All validators must meet certain expectations and protocols as defined by the BitCanna blockchain.

A validator that fails to adhere to these protocols for a certain period puts themself at risk of corrective action. Actions that go against the security and availability of the BitCanna blockchain include the following.

#### &#xD;Downtime&#xD;

When a validator is unavailable to sign blocks within the blockchain, this is called downtime. As a validator, you are expected to take an active role within the chain and contribute to its functionality.&#x20;

The chain, the validator, and any delegators suffer from downtime. Simply put, the fewer validators, the fewer block signs and the lower the rewards for all parties involved. Excessive downtime can also result in slashing, which again impacts the respective validator and its delegators. In BitCanna's case, downtime that exceeds 24 hours will result in slashing.



#### Double Signing

Double signing occurs when a validator signs two blocks at the same block height in the same chain. Because double signing could be exploited and used in malicious actions, BitCanna takes considerable action, making it too costly for all parties involved.



### Consequences&#xD;

Disciplinary action in the form of slashing is taken against a validator's entire BCNA balance. Both the validator and its delegators face repercussions such as slashing or jailing.



#### Jailing&#xD;

Jailing is a means of "detaining" a validator, making them unable to sign blocks and putting them in an [unbonding ](validators-and-delegators.md#unbonding)state so they cannot continue any misconduct. However, because failing to comply with the chain's rules could be accidental, validators can request an un-jailing, allowing them to continue signing blocks.&#x20;

For instance, a local server outage could mean a validator exceeds the downtime limit. However, because the intent was not malicious, validators may request un-jailing. Although severe, jailing helps prevent a validator and all parties involved from continuing misconduct, while simultaneously giving leeway to situations such as server downtime.



#### Balance Slashing&#xD;

This is the slashing of BCNA coins, reducing the validator’s stake by a specified percentage. Balance slashing impacts both the validator and the delegators, reducing voting power and future staking rewards.&#x20;

As these penalties can be quite severe, both validators and delegators should take careful note of the chain's guidelines. For BitCanna-specific rules, please see the [**Chain Parameters**](../token-chain-parameters/chain-parameters.md).

