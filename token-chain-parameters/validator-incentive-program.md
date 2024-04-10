# Validator Incentive Program

The BitCanna chain is supporting the network and the services of BitCanna. Currently 100 validators are securing our blockchain. To reward validators doing more than just validating, but are also offering services to BitCanna we have started a Validator Incentive Program (VIP). Across various categories ranging from technical services to marketing and educational services validators can earn team delegations. This page shows the various categories recognized for the services, how the size of the delegation is determined, how we go about with new rounds of delegations and who has received a delegation in the current round of the VIP (which validator, which service and which size).

### Categories recognized as services for BitCanna

The services we recognize are described below. Per category the description of the service is given and the prerequisite we use to assess eligibility. Services can be rewarded for testnet and mainnet services separately. Prerequisites applied are the following:

* active in governance when a proposal is on chain (measured over the last 10 proposals a participation rate of 80% is required)
* having a maximum commission rate of 20%
* uptime of 99% or higher

For the testnet we recognize explorers, testnet nodes, snapshots, statesync, public RPC nodes, seednodes. The delegation per offered service on the testnet is half (50%) of the same service offered on the mainnet.

* Wallet
  * Description: providing a wallet where users can manage their funds
  * Prerequisite: free validator choice, users should control their own private keys, code should be open-source, wallet needs to be dedicated (so not in combination with an explorer like a fork of ping.pub)
  * Obtained from: [Github](../useful-links/available-tools.md#wallet) (our docs page)
* Explorer
  * Description: providing an explorer to be used to see wallet balances and block history
  * Prerequisite: using own resources (e.g. LCD endpoints. Note; these should not be run from your validator for security reasons), being able to load all blocks from block 1 to the actual block height (the database may not be pruned), data has to be included in **both** files on Github
  * (Mainnet) Obtained from: [Github](../useful-links/available-tools.md#explorer) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/chain-registry.json) (chain registry)
  * (Testnet)  Obtained from: [Github](../useful-links/available-tools.md#testnet-tools) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/devnets/bitcanna-dev-1/chain-registry.json) (testnet chain registry)
* Technical support
  * Description: providing technical support in our Discord channels with fellow validators and the team
  * Prerequisite: quality and amount of the support
  * Obtained from: Google Form for validator submissions
* Testnet nodes
  * Description: supporting the testnet(s)
  * Prerequisite: run a node, being active in testnet governance, available for testnet upgrades, member of the devnet channel in Discord
  * Obtained from: Google Form for validator submissions, [explorer](https://testnet.ping.pub/bitcanna/staking)
* Snapshots
  * Description: providing snapshots to be able to bootstrap a node on the BitCanna network quickly
  * Prerequisite: working link, instruction how to use the snapshot included
  * Obtained from: [Github](../useful-links/available-tools.md#snapshot) (our docs page)
* Statesync
  * Description: providing instruction and method how to statesync a node on the BitCanna network
  * Prerequisite: working link, instruction how to statesync or use the script included, data has to be included in **both** files on Github
  * (Mainnet) Obtained from: [Github](../useful-links/available-tools.md#statesync) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/chain-registry.json) (chain registry)
  * (Testnet)  Obtained from: [Github](../useful-links/available-tools.md#testnet-tools) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/devnets/bitcanna-dev-1/chain-registry.json) (testnet chain registry)
* Archive nodes
  * Description: providing an unpruned database of the blockchain history
  * Prerequisite: approachable via a link, should contain all blocks from the beginning, database must be unpruned
  * Obtained from: [Github](https://github.com/BitCannaGlobal/bcna/blob/main/chain-registry.json) (chain registry)
* Public RPC nodes
  * Description: providing an RPC node where queries can be made to obtain data from the blockchain
  * Prerequisite: accessible URL, tx-index = on, node needs to be synced. Note; these should not be run from your validator node for security reasons (note: on the testnet we allow it)
  * (Mainnet) Obtained from: [Github](https://github.com/BitCannaGlobal/bcna/blob/main/chain-registry.json) (chain registry)
  * (Testnet)  Obtained from: [Github](https://github.com/BitCannaGlobal/bcna/blob/main/devnets/bitcanna-dev-1/chain-registry.json) (testnet chain registry)
* Seednodes
  * Description: providing an seednode used by other nodes to find peers
  * Prerequisite: accessible address, node needs to be synced. Note; these should not be run from your validator node for security reasons. Note: a seednode can't be a persistent peer.
  * (Mainnet) Obtained from: [Github](https://github.com/BitCannaGlobal/bcna/blob/main/chain-registry.json) (chain registry)
  * (Testnet)  Obtained from: [Github](https://github.com/BitCannaGlobal/bcna/blob/main/devnets/bitcanna-dev-1/chain-registry.json) (testnet chain registry)
* Relayers
  * Description: running relayers between chains which are relevant for BitCanna, enabling IBC transactions. This can either be on mainnet or on the testnet, if applicable
  * Prerequisite: active relayer, supporting the right channels, involved in the dedicated Discord group for relayers, relayer address shared with the team, relayer address should show recent IBC transactions in the past 7 days.
  * Obtained from: [SmartStake dashboard](https://relayers.smartstake.io/network/BCNA)
* Data analytics
  * Description: providing data analytics for insights in blockchain usage, delegation statistics, network monitoring, p2p monitoring, chain health monitoring and more
  * Prerequisite: data should be accessible and useable. Advantages if data can be exported and for innovative analyses
  * Obtained from: [Github](../useful-links/available-tools.md#data-analytics) (our docs page)
* Marketing / education
  * Description: providing marketing and education around BitCanna towards (crypto) audience. Content around learning others about the goals of BitCanna and helping us grow (bigger)
  * Prerequisite: high quality marketing and education, easily accessible for interested people, active communication
  * Obtained from: [Discord, BitCanna featured channel ](https://discord.com/channels/805725188355260436/852219092312391722)
* Others
  * Description: all other services which are delivered but which are not included in the aforementioned categories
  * Prerequisite: -
  * Obtained from: Google Form for validator submissions

### Determining the delegation amount

All services will be checked on the mentioned prerequisites. All services are ranked with either a simple “Yes / No” (for example for RPC nodes, statesync; things which either work or don’t work) or are ranked in 3 levels, namely “Small / Medium / Large” based on the audience the service has (for example for explorers and wallets). And lastly we have introduced a level of delegations for new innovation, which will be given to validators who are in the start-up phase of their service which are looking promising or to complete new type of services which are completely different from other services.

For our current delegation program running from November 2023, we have in total a delegation budget of 36 million BCNA for all the categories. A couple of these get a fixed fee:

* Snapshots (150k BCNA delegation)
* Statesync (50k BCNA delegation)
* Archive nodes (1500k BCNA delegation)
* RPC nodes (50k BCNA delegation)
* Seednodes (50k BCNA delegation)
* Relayers (400k BCNA delegation per channel)

After substracting the delegation amount required to reward these services, we distribute the remaining delegation budget over the rest of the services. This is done by giving points for each service. A “Yes” gets 1 point, a “Small” gets 0.5 point, a “Medium” gets 1 point, a “Large” gets 1.5 point and the Innovation tag gets 0.1 point. In our current execution 1 point is worth a delegation of 402232,1429 BCNA. This means that:

* A "Yes" gets a delegation of 402232,1429 BCNA
* A “Small” gets a delegation of 201116,07 BCNA
* A “Medium” gets a delegation of 402232,1429 BCNA
* A “Large” gets a delegation of 603348,21 BCNA
* “Innovation” gets a delegation of 40223,21429 BCNA

### New delegations

Twice a year (last update April 2024) we will review the delegations given. During this period we will also open up the form again, to allow validators with services to subscribe to the program. We will communicate this via our social channels as well as via the validator chats on Discord.

The input received will be assessed and included in the program if approved. Results for the most recent round can be found below.

Note that the amount of $BCNA per earned point can change based on the amount of service providers. So even though your services offered might remain the same, the delegation amount can go up (a bit) or down (a bit) based on the total amount of points rewarded for the services offered by all validators.

### Disclaimer

BitCanna holds the right to review the delegations on other moments besides the a forementioned 2x per year. A script is created which checks the services included in the file on Github to check liveliness and responsivess as well as meeting other requirements like for example running the services on non-validator nodes. This will also apply for services like marketing; long periods of non-compliance with the requirements will have consequences for the delegation.\
\
It can also work the other way around; exceeding expectations can lead to larger delegations.

### Current delegations&#x20;

<table data-header-hidden><thead><tr><th width="202">Validator</th><th width="146">Services</th><th>Delegation [BCNA]</th></tr></thead><tbody><tr><td>AlxVoy ⚡ ANODE.TEAM</td><td>Explorer testnet, Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet</td><td>1179464,286</td></tr><tr><td>ARCTIC</td><td>Testnet node</td><td>402232,1429</td></tr><tr><td>Arcturian Tech</td><td>Testnet node, RPC node mainnet</td><td>452232,1429</td></tr><tr><td>AVIAONE</td><td>Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet</td><td>852232,1429</td></tr><tr><td>bitszn</td><td>Tech support (Medium), Testnet node</td><td>804464,2857</td></tr><tr><td>BlockHunters</td><td>RPC node mainnet, Seednode mainnet</td><td>100000</td></tr><tr><td>BlueStake 🚀</td><td>Snapshots mainnet, RPC node mainnet, Relayer</td><td>600000</td></tr><tr><td>bonded.zone</td><td>Testnet node</td><td>402232,1429</td></tr><tr><td>Cosmostation</td><td>Wallet (Large), Explorer mainnet (Large), Data analytics</td><td>1608928,571</td></tr><tr><td>CosmoWiz</td><td>Testnet node, Data analytics</td><td>804464,2857</td></tr><tr><td>cryptech</td><td>Testnet node, Statesync mainnet, RPC node mainnet</td><td>502232,1429</td></tr><tr><td>Cybernodes</td><td>Testnet node, Relayer, Marketing-education</td><td>1204464,286</td></tr><tr><td>genznodes</td><td>Testnet node, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Relayer</td><td>952232,1429</td></tr><tr><td>GrowVigorously</td><td>Tech support (Medium)</td><td>402232,1429</td></tr><tr><td>Hexnodes</td><td>Tech support (Medium), Testnet node, Snapshots mainnet, Statesync testnet, RPC node mainnet, Seednode mainnet, Relayer</td><td>1479464,286</td></tr><tr><td>Indonode | Bitcanna</td><td>Snapshots mainnet, Statesync mainnet, RPC node mainnet</td><td>250000</td></tr><tr><td>Inter Blockchain Services</td><td>Tech support (Large), Testnet node, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet, Relayer</td><td>1630580,357</td></tr><tr><td>Kalia Network</td><td>Explorer testnet, Testnet node, Snapshots mainnet, Statesync mainnet, RPC node mainnet, Seednode mainnet</td><td>1104464,286</td></tr><tr><td>KitKat</td><td>Tech support (Medium), RPC node mainnet</td><td>452232,1429</td></tr><tr><td>KJINC.io</td><td>Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, RPC node mainnet, RPC node testnet, Seednode mainnet</td><td>802232,1429</td></tr><tr><td>kjnodes</td><td>Explorer testnet, Tech support (Large), Testnet node, Snapshots mainnet, Snapshots testnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet, Relayer, Data analytics</td><td>2610044,643</td></tr><tr><td>KonsorTech</td><td>Explorer testnet, Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet, Relayer, Data analytics</td><td>1981696,429</td></tr><tr><td>L0vd.com</td><td>Explorer testnet, Tech support (Medium), Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet, Relayer</td><td>1981696,429</td></tr><tr><td>Lavender.Five Nodes ?</td><td>Seednode mainnet</td><td>50000</td></tr><tr><td>makimaprjkt</td><td>Testnet node, Snapshots mainnet, Statesync mainnet</td><td>602232,1429</td></tr><tr><td>Midora</td><td>Testnet node</td><td>402232,1429</td></tr><tr><td>MMS</td><td>Snapshots mainnet, Statesync mainnet, RPC node mainnet, Seednode mainnet</td><td>300000</td></tr><tr><td>MultVR</td><td>Testnet node</td><td>402232,1429</td></tr><tr><td>Nodejumper</td><td>Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Data analytics</td><td>1179464,286</td></tr><tr><td>NodeX Emperor</td><td>Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet, Relayer, Data analytics</td><td>1027232,143</td></tr><tr><td>Nodiums</td><td>Testnet node</td><td>402232,1429</td></tr><tr><td>Oldcat</td><td>Testnet node, Seednode mainnet</td><td>452232,1429</td></tr><tr><td>Panthea EU</td><td>Snapshots mainnet, Statesync mainnet, RPC node mainnet, Seednode mainnet, Relayer</td><td>700000</td></tr><tr><td>Paranormal</td><td>Snapshots mainnet, Statesync mainnet, RPC node mainnet, Data analytics</td><td>652232,1429</td></tr><tr><td>Ping.pub</td><td>Wallet (Large), Explorer mainnet (Large), Explorer testnet, Statesync mainnet</td><td>1658928,571</td></tr><tr><td>polkachu</td><td>Snapshots mainnet, Statesync mainnet, RPC node mainnet, Relayer, Data analytics</td><td>1052232,143</td></tr><tr><td>Safe Block</td><td>Testnet node, Snapshots mainnet, Statesync mainnet, RPC node mainnet</td><td>652232,1429</td></tr><tr><td>SGTStake</td><td>Archive Node, RPC node mainnet</td><td>1550000</td></tr><tr><td>Stake.Works | Bitcanna</td><td>Testnet node</td><td>402232,1429</td></tr><tr><td>Stakely</td><td>Tech support (Medium)</td><td>402232,1429</td></tr><tr><td>tRDM | Nodera</td><td>Testnet node</td><td>402232,1429</td></tr><tr><td>ValidatorNode</td><td>RPC node mainnet</td><td>50000</td></tr><tr><td>🐔 The Chicken Coop 🦝 Homestead</td><td>Tech support (Large), RPC node mainnet, Relayer</td><td>1053348,214</td></tr><tr><td>🔥STAVR🔥 REStake ON✅</td><td>Explorer testnet, Testnet node, Snapshots mainnet, Statesync mainnet, RPC node mainnet, Relayer</td><td>1454464,286</td></tr></tbody></table>

