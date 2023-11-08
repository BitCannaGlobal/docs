# Validator Incentive Program

The BitCanna chain is supporting the network and the services of BitCanna. Currently 100 validators are securing our blockchain. To reward validators doing more than just validating, but are also offering services to BitCanna we have started a Validator Incentive Program (VIP). Across various categories ranging from technical services to marketing and educational services validators can earn team delegations. This page shows the various categories recognized for the services, how the size of the delegation is determined, how we go about with new rounds of delegations and who has received a delegation in the current round of the VIP (which validator, which service and which size).

### Categories recognized as services for BitCanna

The services we recognize are described below. Per category the description of the service is given and the prerequisite we use to assess eligibility. Services can be rewarded for testnet and mainnet services separately.&#x20;

For the testnet we recognize explorers, testnet nodes, snapshots, statesync, public RPC nodes, seednodes. The delegation per offered service on the testnet is half (50%) of the same service offered on the mainnet.

* Wallet
  * Description: providing a wallet where users can manage their funds
  * Prerequisite: free validator choice, users should control their own private keys, code should be open-source, wallet needs to be dedicated (so not in combination with an explorer like a fork of ping.pub)
  * Obtained from: [Github](../tools/available-tools.md#wallet) (our docs page)
* Explorer
  * Description: providing an explorer to be used to see wallet balances and block history
  * Prerequisite: using own resources (e.g. LCD endpoints. Note; these should not be run from your validator for security reasons), being able to load all blocks from block 1 to the actual block height (the database may not be pruned)
  * (Mainnet) Obtained from: [Github](../tools/available-tools.md#explorer) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/chain-registry.json) (chain registry)
  * (Testnet)  Obtained from: [Github](../tools/available-tools.md#explorer) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/devnets/bitcanna-dev-1/chain-registry.json) (testnet chain registry)
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
  * Obtained from: [Github](../tools/available-tools.md#snapshot) (our docs page)
* Statesync
  * Description: providing instruction and method how to statesync a node on the BitCanna network
  * Prerequisite: working link, instruction how to statesync or use the script included
  * (Mainnet) Obtained from: [Github](../tools/available-tools.md#statesync) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/chain-registry.json) (chain registry)
  * (Testnet)  Obtained from: [Github](../tools/available-tools.md#explorer) (our docs page) & [Github](https://github.com/BitCannaGlobal/bcna/blob/main/devnets/bitcanna-dev-1/chain-registry.json) (testnet chain registry)
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
  * Obtained from: [Github](../tools/available-tools.md#data-analytics) (our docs page)
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

After substracting the delegation amount required to reward these services, we distribute the remaining delegation budget over the rest of the services. This is done by giving points for each service. A “Yes” gets 1 point, a “Small” gets 0.5 point, a “Medium” gets 1 point, a “Large” gets 1.5 point and the Innovation tag gets 0.1 point. In our current execution 1 point is worth a delegation of 316333,33 BCNA. This means that:

* A "Yes" gets a delegation of 316333,33 BCNA
* A “Small” gets a delegation of 158166,66 BCNA
* A “Medium” gets a delegation of 316333,33 BCNA
* A “Large” gets a delegation of 474500 BCNA
* “Innovation” gets a delegation of 31633,333 BCNA

### New delegations

Every 4 months (so 3 times per year; in January, May and September) we will review the delegations given. During this period we will also open up the form again, to allow validators with services to subscribe to the program. We will communicate this via our social channels as well as via the validator chats on Discord.

The input received will be assessed and included in the program if approved. Results for the most recent round can be found below.

Note that the amount of $BCNA per earned point can change based on the amount of service providers. So even though your services offered might remain the same, the delegation amount can go up (a bit) or down (a bit) based on the total amount of points rewarded for the services offered by all validators.

### Disclaimer

BitCanna holds the right to review the delegations on other moments besides the aforementioned 3x per year (every 4 months). A script is created which checks the services included in the file on Github to check liveliness and responsivess as well as meeting other requirements like for example running the services on non-validator nodes. This will also apply for services like marketing; long periods of non-compliance with the requirements will have consequences for the delegation.\
\
It can also work the other way around; exceeding expectations can lead to larger delegations.

### Current delegations&#x20;

<table data-header-hidden><thead><tr><th width="202">Validator</th><th>Services</th><th>Delegation [BCNA]</th></tr></thead><tbody><tr><td>AlxVoy</td><td>Explorer testnet, Tech support, Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet</td><td>1324000</td></tr><tr><td>ArcturianTech</td><td>Tech support (Large), Testnet node, RPC node mainnet, Others live</td><td>1157166,66</td></tr><tr><td>AVIAONE</td><td>Tech support (Large), Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet</td><td>1240833,33</td></tr><tr><td>bitszn</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>BlockHunters</td><td>Testnet node, RPC node mainnet, Seednode mainnet</td><td>416333,33</td></tr><tr><td>bonded.zone</td><td>Testnet node, Statesync mainnet</td><td>366333,33</td></tr><tr><td>cardex</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>Cosmostation</td><td>Wallet (Large), Explorer mainnet (Large), Data analytics (Large)</td><td>1423500</td></tr><tr><td>CosmoWiz</td><td>Testnet node, Data analytics (Medium)</td><td>632666,66</td></tr><tr><td>cryptech</td><td>Testnet node, Statesync mainnet</td><td>366333,33</td></tr><tr><td>CryptoSailors</td><td>Snapshots mainnet</td><td>150000</td></tr><tr><td>Cybernodes</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>DoubleTop</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>F-Staking</td><td>Others live (Innovation)</td><td>31633,333</td></tr><tr><td>genznodes</td><td>Tech support, Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode testnet, Relayer</td><td>1432666,66</td></tr><tr><td>GrowVigorously</td><td>Tech support</td><td>316333,33</td></tr><tr><td>Hexnodes</td><td>Testnet node, Snapshots mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet</td><td>641333,33</td></tr><tr><td>Indonode</td><td>Tech support, Snapshots mainnet, Statesync mainnet</td><td>516333,33</td></tr><tr><td>Inter Blockchain Services</td><td>Tech support, Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednode testnet, Relayer</td><td>1407666,66</td></tr><tr><td>Kalia</td><td>Testnet node, Snapshots mainnet</td><td>466333,33</td></tr><tr><td>KitKat</td><td>RPC node mainnet</td><td>50000</td></tr><tr><td>KJINC</td><td>Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, RPC node mainnet, RPC node testnet</td><td>666333,33</td></tr><tr><td>kjnodes</td><td>Explorer testnet, Tech support (Large), Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Seednode mainnet, Seednodeestnet, Relayer, Data analytics (Large),</td><td>2431666,66</td></tr><tr><td>konsortech</td><td>Explorer testnet, Tech support, Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet</td><td>1249000</td></tr><tr><td>L0vd</td><td>Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet</td><td>616333,33</td></tr><tr><td>Lavender.Five Nodes</td><td>Seednode mainnet</td><td>50000</td></tr><tr><td>makimaprjkt</td><td>Testnet node, Snapshots mainnet, Statesync mainnet, RPC node mainnet, Seednode mainnet, Relayer</td><td>1016333,33</td></tr><tr><td>midora</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>MMS</td><td>Testnet node, Snapshots mainnet, Statesync mainnet, RPC node mainnet, Seednode mainnet</td><td>616333,33</td></tr><tr><td>MultVR</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>Node&#x26;Validator VN</td><td>Tech support</td><td>316333,33</td></tr><tr><td>Nodejumper</td><td>Tech support, Testnet node, Snapshots mainnet, Snapshots testnet, Statesync mainnet, Statesync testnet, RPC node mainnet, RPC node testnet, Data analytics (Large)</td><td>1482166,66</td></tr><tr><td>NodeX Emperor</td><td>Explorer testnet, Tech support, Testnet node, Snapshots mainnet, Statesync mainnet, Statesync testnet, RPC node mainnet, Seednode mainnet, Data analytics (Medium)</td><td>1590333,33</td></tr><tr><td>Nodiums</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>Notional</td><td>RPC node mainnet, Relayer</td><td>450000</td></tr><tr><td>Oldcat</td><td>Testnet node, Seednode mainnet</td><td>366333,33</td></tr><tr><td>Pandora</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>Panthea</td><td>Tech support, Snapshots mainnet, Statesync mainnet, RPC node mainnet, Seednode mainnet, Relayer</td><td>1016333,33</td></tr><tr><td>Paranormal</td><td>Tech support, Snapshots mainnet, Statesync mainnet, RPC node mainnet, Data analytics (Large), Others live (Innovation)</td><td>1072466,66</td></tr><tr><td>Ping</td><td>Wallet (Large), Explorer mainnet (Large), Explorer testnet, Statesync mainnet</td><td>1315333,33</td></tr><tr><td>Podocasts</td><td>Marketing-education</td><td>316333,33</td></tr><tr><td>Polkachu</td><td>Snapshots mainnet, Statesync mainnet, RPC node mainnet, Relayer, Data analytics (Medium)</td><td>966333,33</td></tr><tr><td>Safe Block</td><td>Tech support, Testnet node, Snapshots mainnet, RPC node mainnet</td><td>832666,66</td></tr><tr><td>SGTstake</td><td>Archive Node, RPC node mainnet</td><td>1550000</td></tr><tr><td>SmartNodes</td><td>Marketing-education</td><td>316333,33</td></tr><tr><td>Stake.Works</td><td>Testnet node</td><td>316333,33</td></tr><tr><td>Stakely</td><td>RPC node mainnet, Relayer</td><td>450000</td></tr><tr><td>StakePool</td><td>Tech support (Large), Snapshots mainnet, Statesync mainnet</td><td>674500</td></tr><tr><td>STAVR</td><td>Explorer testnet, Tech support, Testnet node, Snapshots mainnet, Statesync mainnet, RPC node mainnet, Relayer</td><td>1599000</td></tr><tr><td>The Silver Fox</td><td>Explorer testnet, Testnet node, Statesync mainnet, Statesync testnet</td><td>707666,66</td></tr><tr><td>ValidatorNode</td><td>RPC node mainnet</td><td>50000</td></tr><tr><td>🐔 The Chicken Coop 🦝</td><td>Tech support (Large), Relayer, Others live</td><td>1190833,33</td></tr></tbody></table>

