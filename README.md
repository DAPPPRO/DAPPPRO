Dapp.pro and DAPP network
Dapp.pro's mission is to promote large-scale application of distributed applications (dApps) by introducing a set of technology solutions: "DAPP Network", which makes development on the blockchain easier and more affordable. Start.

Despite the maturity and popularity of blockchain technology, it is still difficult to exploit its potential. One of the reasons for this disconnect is the lack of decentralized applications or dApps that provide key utilities and compelling experiences for mainstream users. "Killer-level app" refers to an application that naturally increases usage to a certain percentage of people (regularly used) - without having to have an in-depth understanding of the underlying technologies (such as the TCP/IP protocol behind the Internet). While consumer applications like CryptoKitties showcase current scaling challenges on platforms such as Ethereum, the dynamic developer and dApps ecosystem is still evolving. Today, the most popular dApp is in the game,
Online gambling and communication categories - but tomorrow, their features and coverage may be as broad as the Internet.

With the emergence of competitors in the Ethereum blockchain platform, new technical challenges and opportunities have emerged. Although the EOS blockchain may bring unlimited scale and speed, the RAM and CPU resources required to run on the EOS blockchain are not cheap, limited, and are expected to become more successful due to successful adoption - creating chicken and An egg-constrained ecosystem. A technical solution is needed to make it easy for dApp developers to externalize CPU and RAM from the EOS blockchain and take advantage of the functionality normally required in an accessible and affordable way.

Dapp.pro is proud to introduce the DAPP Network Native Node called "DAPP", a multi-purpose utility node designed to power the ecosystem of utilities, resources and services, specifically for user-centric dApp developer needs

The DAPP network paved the way for the emergence of new, decentralized applications - those applications that were previously unimaginable due to the systemic limitations of the prior art stack. By introducing a new collaboration and motivation ecosystem, it is likely that there will be a long tail of truly diverse, creative and useful dApps.

Dapp.pro introduced the first utility of the DAPP node - the DAPP.PRO/RAM system. DAPP.PRO/RAM is an alternative storage solution for developers developing EOS dApps that is compatible with existing RAM systems, decentralized and cost-effective to store and retrieve an unlimited amount of data.

Dapp.pro released the first key product supported by DAPP nodes to the community, providing tools for developers to build and create DAPP networks. With this vision in mind, dapp.pro has developed a roadmap that provides developers with continuous tools and services that can help dApp scalability. The development of the DAPP network aims to improve the convenience, speed and affordability of building scalable dApps on the blockchain today.


First, DAPP.PRO/RAM system

The EOS blockchain represents an important milestone in the development of the public blockchain. The market value is over $2,200,000,000 and approximately. 10,000 new accounts per week (as of January 14, 2019), with powerful processing capabilities to support the next wave of paradigm conversion dApp.pro

The first use of the DAPP.pro node was designed to enhance one of the core functions of the EOS blockchain, RAM (a resource for storing data).

In order to develop on EOS, dApp developers must own and use RAM. Currently, there are two main reasons for the limited use of RAM: its price exceeds 58 EOS / 1MB (as of February 14, 2019), and the supply has a ceiling, currently about 90GB (expected to January 31, 2019) Will increase to 129GB)), which severely limits the functionality of dApp developers and their applications.

The DAPP.PRO/RAM system ("DAPP.PRO/RAM") introduces three innovations for blockchain developers:

1. Reasonable storage space.
2. There may be an unlimited amount of storage.
3, chain integrity down chain processing

DAPP.PRO/RAM is another storage solution for developers building EOS dApps that are RAM-compatible, decentralized and designed to make it affordable and efficient to store and retrieve an unlimited amount of data. In addition, DAPP.PRO/RAM intends to eliminate the current correlation between memory (RAM) cost and smart contract size (requires storage) by using RAM as a cache.

Today, dApp developers are limited in their efforts to build EOS because they have difficulty paying for RAM and/or the RAM they need for their dApps far exceeds the current total supply. With the introduction

DAPP.PRO/RAM is a complement to RAM, and dApp developers will be able to contemplate new decentralized applications and user interactions that are prohibited by today's technology limitations.

II.DAPP.PRO/RAM system components

The DAPP.PRO/RAM system consists of the following main components:
DAPP.PRO node: The first use of the DAPP node allows you to interact with RAM as a cache. EOS contracts can only read and write data from the actual RAM. To provide additional capacity, DAPP.PRO/RAM introduces a mechanism that uses DAPP.PRO nodes to load data from DAPP.PRO/RAM into RAM in a decentralized and untrusted manner. The DAPP.PRO node will be used as an application access node for the DAPP.PRO/RAM system to access and use the system's read and write functions. The DAPP.PRO node does not grant other rights. The DAPP.PRO node can also be enabled on other blockchains and needs to be staked out by the dApp developer to enable it to use DAPP.PRO/RAM.
● DAPP.PRO node smart contract: manages the shares of the DAPP.PRO node required to access the DAPP.PRO/RAM system and enable its functions.
DAPP.PRO/RAM library: Any smart contract that uses DAPP.PRO/RAM instead of RAM includes the DAPP.PRO/RAM library, which enables the user contract to be the same as the RAM table (multiple index table). Reading and writing in the programming interface.
• dApp Service Provider (“DSP”): Anyone who operates a server running a DSP node (defined below). The DSP may provide a customized service package that includes: the amount of storage space used, the specifications of the server, and the amount of corresponding DAPP.PRO nodes ("DSP Service Packs") that must be owned to use each package.
• DSP node: The DAPP.PRO/RAM network consists of nodes operated by the dApp service provider. The DSP node acts as a redundant and untrusted store of data in the network. Each node provides an EOSIO API service to which the dApp submits its transaction ("TX") so that the contract can access the relevant data before performing the operation.
● User Contract: The standard code provided by the EOS dApp developer, including the dApps.DAPP.PRO/RAM library, so that DAPP.PRO/RAM can be used for compatibility and operation. The user contract interacts with the DAPP.PRO/RAM system as long as the user contract is equipped with a sufficient number of DAPP nodes to support the read/write requirements of the dApp.

IIIDAPP.PRO/.RAM system operation

A. Settings

In order to use the DAPP.PRO/RAM system, the dApp developer needs to do the following:

1) Integrate the DAPP.PRO/RAM library into the user contract, from which data is written to or read from the DAPP.PRO/RAM database.
2) Select the DSP service package that meets the initial dApp data storage and access requirements.
3) Obtain the applicable number of DAPP.PRO tokens to accommodate the required data storage and access requirements.
4) Obtain the DAPP token in the user contract through the DAPP.PRO/RAM library, assign the mortgage token to the specific DSP data store, and access the software package selected by the dApp developer.
5) You can use unused DAPP tokens to vote for DSPs that you think support and strengthen your community.



Similar to RAM, dApp developers need to monitor their DAPP.PRO/RAM usage (and the number of DAPP.PRO nodes collateralized) and change their selected DSP service packs as needed to avoid resource shortages (for example, service plans are too small) Service interruption due to insufficient service. The DAPP.PRO node has been staked out).



C. Processing TX with DAPP.PRO/RAM system

The process of executing TX on a user contract is as follows:

1) The client sends a standard TX to the user contract using DAPP.PRO/RAM. The TX is sent through the EOSIO API of the DSP node.
2) The DSP node detects all the data needed for TX, which is not found on RAM (because it has not been written yet), but exists on DAPP.PRO/RAM (see section 1 above):
a) DSP performs operations on locally synchronized EOS nodes
b) The user contract runs the transaction locally, and when it tries to access the required data, it throws an exception (assertion failure). If data is missing from RAM, this exception can be thought of as a way to signal the DSP to request its service.
c) The DSP catches the exception and parses the service request.
3) The DSP verifies that the dApp developer has enough DAPP nodes to stake out.
4) The DSP node relays the data and the proof of the encryption validity of the data to the user contract. This is called a "pre-request."
5) The user contract verifies the encryption certificate and loads the data into RAM.
6) The DSP sends the actual TX from the client to the user contract. At this point, all the necessary data is in RAM.
7) If the user contract requires modification of the data stored in DAPP.PRO/RAM, it will schedule an event using the new data captured by the DSP, which will cache it locally. Now, new data appears in the chain history.
8) The user contract calculates and stores the signature required for the password proof for use in the next reading, and also saves the data in RAM.
9) The user contract signals the DSP to clear the data from the RAM (using a transaction output (eg, console output field) to perform signal transmission).
10) The DSP sends an operation (clear) to the user contract, the user contract deletes the data from the RAM, while retaining the signature to verify the integrity of the next warm-up request. As mentioned above, there is no data loss because it is part of the chain history.


D. Cross-chain function of DAPP.PRO/RAM system

The DAPP.PRO/RAM system can also act as shared memory between chains. By passing DAPP.PRO/RAM data pointers (such as IPFS pointers) between chains, they will be available to DSPs in multiple chains. Thus, once IBC (inter-block communication) is available, the DAPP.PRO/RAM system will allow unlimited "IBC bandwidth" in addition to its core functionality.



IV.DAPP Service Provider (DSP)

Any individual or entity can become a DSP. The DSP remains completely autonomous in all aspects of its operation. Customized data packages are available for each DSP with pre-defined terms as determined by the DSP.

As defined in the "DAPP Node Distribution Mechanism" section below, the DSP is motivated by the expansion of the DAPP node.

A. DSP function
o Standard API endpoints for the EOS blockchain.
○ Warm-up: User contracts have a temporary cache (stored in standard RAM). Whenever an action is called, the DSP simulates the action and collects all the necessary data points needed for the action. The DSP then sends a warm-up request - a request containing data points and cryptographic signatures for those data points. After being verified by the user contract, this request will be temporarily loaded into the temporary RAM cache table.
○ Proof/data indexing of the selected data set: The actual DAPP.PRO/RAM data and proofs have been effectively stored in the chain history. In order to provide quick access to these elements when performing a "warm-up request", the DSP listens to block history in real time and stores the latest versions and certificates of different data points in accessible locations (eg IPFS, S3, disk, SQL).
○ DSP allows for many other custom external services, many of which will be created by the community, some of which are outlined in the roadmap section below.
V.DAPP network system model

• In order to gain access to DSP-promoted DAPP.PRO/RAM systems and services, dApp developers must mortgage DAPP nodes in user contracts. The number of DAPP nodes required in each user contract shall be the number of applicable DAPP nodes required to meet the read/write requirements of the dApp and shall match the selected DSP encapsulation requirements. Please note that dApp developers may need to invest more than the minimum amount to vote for a particular DSP.
• The dApp developer may maintain multiple DAPP nodes assigned to enable services from different DSPs. This is especially to ensure service redundancy in the case of potential DSP unavailability.
● The DAPP.PRO smart contract will continue to generate new DAPP.PRO coins with an annual allocation rate ranging from 1-5% ("inflation"), which will apply to the total supply of DAPP.PRO. DAPP node smart contract allocates inflation to DSP
It is proportional to the number of DAPP nodes that are staked out and assigned to the DSP. The stakeout amount is calculated in units of accumulated blocks, and is distributed on a cycle basis. Initially, the inflation rate was set at 1.71%. Thereafter, the community may update the inflation rate from time to time to an annual inflation rate between 1% and 3%.
• In order to receive an inflation DAPP node, the DSP must request a node from the DAPP Generator smart contact. After the first time the DAPP node is staked out into one of its service packs, the DSP can declare for the first time that the DAPP node is only one block. After the DSP claims the DAPP node, he will not be able to apply again until he has applied for at least 24 hours last time, and so on.
 DAPP.PRO Ricardian Contract Ricardo Contract Income Ecology

Mortgage node
10EOS, 10,000 EOS, mortgage 3 times 0.5% - 1.5% mining

Sharing node
One star: Mortgage is a star. The first generation earned 100%.

Two stars: 3 people directly pushed, 10 people in the team. The first generation of revenue is 100%, and the second generation of revenue is 40%.

Samsung: Directly push three or two stars. The first generation income is 100%, the second generation income is 40%, and the third generation income is 20%.

Four stars: Push four stars directly. The first generation income is 100%, the second generation income is 40%, the third generation income is 20%, and the fourth generation income is 2%.

Five stars: five two stars. The first generation income is 100%, the second generation income is 40%, the third generation income is 20%, the fourth generation income is 2%, and the second generation income is 2%.

Six stars: Push a five star straight and then push the five stars toward yourself. First generation income 100%, second generation income 40%, third generation income 20%, fourth generation income 2%, unlimited generation income 2%, and participate in global dividend top 10
