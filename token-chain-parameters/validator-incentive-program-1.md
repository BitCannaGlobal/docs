# Validator Incentive Program (from 01-10-2023)

The BitCanna chain is supporting the network and the services of BitCanna. Currently 100 validators are securing our blockchain. To reward validators doing more than just validating, but are also offering services to BitCanna we have started a Validator Incentive Program (VIP). Across various categories ranging from technical services to marketing and educational services validators can earn team delegations. This page shows the various categories recognized for the services, how the size of the delegation is determined, how we go about with new rounds of delegations and who has received a delegation in the current round of the VIP (which validator, which service and which size).

### Categories recognized as services for BitCanna

The services we recognize are described below. Per category the description of the service is given and the prerequisite we use to assess eligibility. Services can be rewarded for testnet and mainnet services separately.

* Wallet
  * Description: providing a wallet where users can manage their funds
  * Prerequisite: free validator choice, users should control their own private keys, code should be open-source
  * Obtained from: [Github](../tools/available-tools.md#wallet)
* Explorer
  * Description: providing an explorer to be used to see wallet balances and block history
  * Prerequisite: using own resources (e.g. LCD endpoints. Note; these should not be run from your validator for security reasons), being able to load all blocks from block 1 to the actual block height (the database may not be pruned)
  * Obtained from: [Github](../tools/available-tools.md#explorer)
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
  * Obtained from: [Github](../tools/available-tools.md#snapshot)
* Statesync
  * Description: providing instruction and method how to statesync a node on the BitCanna network
  * Prerequisite: working link, instruction how to statesync or use the script included
  * Obtained from: [Github](../tools/available-tools.md#statesync)
* Archive nodes
  * Description: providing an unpruned database of the blockchain history
  * Prerequisite: approachable via a link, should contain all blocks from the beginning, database must be unpruned
  * Obtained from: Google Form for validator submissions, will be put into the chain registry file on Github (link to be included)
* Public RPC nodes
  * Description: providing an RPC node where queries can be made to obtain data from the blockchain
  * Prerequisite: accessible URL, tx-index = on, node needs to be synced. Note; these should not be run from your validator node for security reasons.
  * Obtained from: [Github](https://github.com/cosmos/chain-registry/blob/master/bitcanna/chain.json)
* Seednodes
  * Description: providing an seednode used by other nodes to find peers
  * Prerequisite: accessible URL, node needs to be synced. Note; these should not be run from your validator node for security reasons.
  * Obtained from: [Github](https://github.com/cosmos/chain-registry/blob/master/bitcanna/chain.json)
* Relayers
  * Description: running relayers between chains which are relevant for BitCanna, enabling IBC transactions. This can either be on mainnet or on the testnet, if applicable
  * Prerequisite: active relayer, supporting the right channels, involved in the dedicated Discord group for relayers, relayer address shared with the team, relayer address should show recent IBC transactions in the past 7 days. More active relayers are rewarded higher.
  * Obtained from: [SmartStake dashboard](https://relayers.smartstake.io/network/BCNA)
* Data analytics
  * Description: providing data analytics for insights in blockchain usage, delegation statistics, network monitoring, p2p monitoring, chain health monitoring and more
  * Prerequisite: data should be accessible and useable. Advantages if data can be exported and for innovative analyses
  * Obtained from: [Github](../tools/available-tools.md#data-analytics)
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

For our current delegation program running from June 2023, we have in total a delegation budget of 36 million BCNA for all the categories (note: due to some corrections after the delegations were done this amount is increased to 36.15 million BCNA). A couple of these get a fixed fee:

* Snapshots (150k BCNA delegation)
* Statesync (40k BCNA delegation)
* Archive nodes (750k BCNA delegation)
* RPC nodes (40k BCNA delegation)
* Relayers (200k BCNA delegation per channel)

After substracting the delegation amount required to reward these services, we distribute the remaining delegation budget over the rest of the services. This is done by giving points for each service. A “Yes” gets 1 point, a “Small” gets 0.5 point, a “Medium” gets 1 point, a “Large” gets 1.5 point and the Innovation tag gets 0.1 point. In our current execution 1 point is worth a delegation of 216462.59 BCNA. This means that:

* A "Yes" gets a delegation of 216462.59 BCNA
* A “Small” gets a delegation of 108231.29 BCNA
* A “Medium” gets a delegation of 216462.59 BCNA
* A “Large” gets a delegation of 324693.88 BCNA
* “Innovation” gets a delegation of 21646.26 BCNA

### New delegations

Every 4 months (so 3 times per year; in January, May and September) we will review the delegations given. During this period we will also open up the form again, to allow validators with services to subscribe to the program. We will communicate this via our social channels as well as via the validator chats on Discord.

The input received will be assessed and included in the program if approved. Results for the most recent round can be found below.

Note that the amount of $BCNA per earned point can change based on the amount of service providers. So even though your services offered might remain the same, the delegation amount can go up (a bit) or down (a bit) based on the total amount of points rewarded for the services offered by all validators.

### Current delegations&#x20;

| polkachu.com                                | Tech support (Medium), Snapshots, Statesync, RPC node, Relayer (2), Data analytics                                      | <p>1062925,17</p><p> </p> |
| ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| 🐔 The Chicken Coop 🦝                      | Tech support (Medium), Relayer (2)                                                                                      | 616462,585                |
| jabbey                                      | Tech support (Small)                                                                                                    | 108231,2925               |
| KJINC.io                                    | Testnet node, Snapshots, RPC node, Relayer (2)                                                                          | 806462,585                |
| SGTstake                                    | Archive Node, RPC node                                                                                                  | 790000                    |
| Cosmostation                                | Wallet (Large), Explorer (Large), Tech support (Small), Data analytics                                                  | 974081,6327               |
| kjnodes                                     | Explorer, Tech support (Small), Testnet node, Snapshots, Statesync, RPC node, Relayer (3), Others live (Medium)         | 1587619,048               |
| mintthemoon                                 | Tech support (Small), Statesync, RPC node                                                                               | 188231,2925               |
| Safe Block                                  | Testnet node, Statesync, RPC node, Relayer (1)                                                                          | 496462,585                |
| Stake.Works \| Bitcanna                     | Tech support (Small), Testnet node                                                                                      | 324693,8776               |
| Stakeme.io                                  | Snapshots, Statesync, Others live (Small)                                                                               | 298231,2925               |
| genznodes                                   | Snapshots, Statesync, RPC node, Relayer (3)                                                                             | 830000                    |
| Indonode                                    | Testnet node, Snapshots, Statesync, Relayer (3)                                                                         | 1006462,585               |
| AVIAONE                                     | Tech support (Large), Testnet node, Snapshots, Statesync, RPC node, Marketing-education (Large), Others live (Medium)   | 1312312,925               |
| BlockHunters 🎯                             | Testnet node, RPC node, Relayer (4)                                                                                     | 1056462,585               |
| AlxVoy ⚡ ANODE.TEAM                         | Testnet node, Snapshots, Statesync, Relayer (2)                                                                         | 806462,585                |
| 🦊 The Silver Fox                           | Tech support (Medium), Testnet node                                                                                     | 432925,1701               |
| bonded.zone ⚡                               | Testnet node, Statesync, Marketing-education (Small)                                                                    | 364693,8776               |
| 🔥STAVR🔥                                   | Explorer, Tech support (Medium), Testnet node, Snapshots, Statesync, RPC node, Relayer (3), Others live (Small)         | 1587619,048               |
| Midora                                      | Testnet node                                                                                                            | 216462,585                |
| KonsorTech                                  | Wallet (Small), Testnet node, Snapshots, Statesync, RPC node, Relayer (3)                                               | 1154693,878               |
| NODEJUMPER                                  | Testnet node, Snapshots, Statesync, RPC node, Relayer (2), Data analytics, Others live (Small)                          | 1171156,463               |
| Panthea EU                                  | Snapshots, Statesync, RPC node, Relayer (3), Others live (Medium)                                                       | 1046462,585               |
| cryptech                                    | Testnet node, Statesync                                                                                                 | 256462,585                |
| Cryptosailors                               | Testnet node, Snapshots, Statesync                                                                                      | 406462,585                |
| Stakely.io                                  | RPC node, Relayer (2), Marketing-education (Small), Others live (Medium)                                                | 764693,8776               |
| maxfoton                                    | Statesync                                                                                                               | 40000                     |
| Cybernodes                                  | Testnet node, Marketing-education (Small), Others live (Small)                                                          | 432925,1701               |
| Hexnodes                                    | Testnet node, Snapshots, Statesync, RPC node, Relayer (1), Marketing-education (Small)                                  | 754693,8776               |
| Oldcat                                      | Testnet node                                                                                                            | 216462,585                |
| Citizen Cosmos                              | Marketing-education (Small)                                                                                             | 108231,2925               |
| L0vd.com                                    | Snapshots, Statesync, RPC node, Relayer (1), Others live (Small)                                                        | 538231,2925               |
| Inter Blockchain Services                   | Tech support (Medium), Testnet node, Snapshots, Statesync, RPC node, Relayer (6)                                        | 1862925,17                |
| arcryptorg                                  | RPC node                                                                                                                | 40000                     |
| CosmoWiz                                    | Testnet node, Snapshots, Archive Node, RPC node, Relayer (5), Data analytics                                            | 2372925,17                |
| Paranormal Funky Bros.                      | Tech support (Medium), Testnet node, Snapshots, RPC node, Data analytics                                                | 839387,7551               |
| Arcturian Tech                              | Explorer (Small), Tech support (Large), Testnet node, Marketing-education (Small)                                       | 757619,0476               |
| Stakewolle.com \| Auto-compound             | Others live (Small)                                                                                                     | 108231,2925               |
| bitszn                                      | Tech support (Small), Testnet node, Statesync, Archive Node, RPC node, Relayer (5), Data analytics, Others live (Small) | 2479387,755               |
| Kalia Network                               | Wallet (Medium), Explorer (Medium), Testnet node, Snapshots, Statesync                                                  | 839387,7551               |
| POSTCAPITALIST🎩 \| soon rename to DOBLETOP | Testnet node, Data analytics                                                                                            | 432925,1701               |
| ALKIA 🟢🟢🟢                                | Statesync, Data analytics                                                                                               | 256462,585                |
| Nodiums                                     | Tech support (Small), Testnet node, Statesync, Archive Node, Relayer (5)                                                | 2114693,878               |
| MMS                                         | Testnet node, RPC node, Relayer (1), Marketing-education (Small), Others live (Medium)                                  | 781156,4626               |
| ⚛️NodeOf Cosmonauts - BitCanna🧑‍🚀         | Tech support (Small), Archive Node                                                                                      | 858231,2925               |
| ping.pub                                    | Wallet (Large), Explorer (Large)                                                                                        | 649387,7551               |
| MultVR                                      | Testnet node                                                                                                            | 216462.59                 |
| StakePool                                   | Tech support (Medium), Statesync, RPC node                                                                              | 296462.59                 |
| SmartNodes                                  | Marketing (Medium)                                                                                                      | 216462.59                 |

