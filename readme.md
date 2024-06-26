<p align="center">
<img style="margin: 0 auto; width: 300px; height: 100%;" src="https://raw.githubusercontent.com/arif98741/smb/master/img/smb-logo.png">
</p>

<!-- TOC -->
  * [WELCOME TO SOCIAL MEDIA BUDDY](#welcome-to-social-media-buddy)
    * [INTRODUCTION](#introduction)
  * [WHAT IS SOCIAL MEDIA BUDDY?](#what-is-social-media-buddy)
  * [WHAT IS SMBT ?](#what-is-smbt-)
  * [WHAT IS SMBC ?](#what-is-smbc-)
  * [TECHNICAL UNDERPINNINGS:](#technical-underpinnings)
  * [PROBLEM](#p-stylealign-center-text-align-centerspan-stylecolor-redproblemspanp)
  * [SOLUTION](#p-stylealign-center-text-align-centerspan-stylecolor-redsolutionspanp)
<!-- TOC -->

Welcome to Social Media Buddy



## WELCOME TO SOCIAL MEDIA BUDDY
### INTRODUCTION
We now live in an ever-changing world of digital technology; people have embraced social media as an everyday part of their lives social media refers to a variety of technologies that facilitate the sharing of ideas and information among their users. Across our globe billions of people engage using numerous means of social media to communicate and possibly more importantly to create revenue for themselves by creating content to entertain and educate people from all walks of life.

One of the newest technologies being accepted and introduced into people’s lives is Blockchain, blockchain is a distributed database or ledger shared among a computer network nodes. They are best known for their crucial role in cryptocurrency systems for maintaining a secure and decentralized record of transactions, but they are not limited to cryptocurrency uses.
Blockchains can be used to make data in any industry immutable, the term used to describe the inability to be altered, coupled with Crypto Currencies a digital currency in which transactions are verified and records maintained by a decentralized system using cryptography, rather than by a centralized authority our aim is to give both content creators and viewers the opportunity to generate wealth for themselves whilst using the various social media platforms.

Social Media Buddy understands that Digital Currencies and Blockchain are rapidly expanding and global adoption will be upon us in the blink of an eye, with this in mind we have made it our absolute goal to give social media users as a whole a revolutionary way to expand their wealth by doing nothing different than engaging in the everyday activities they already participate in.

## WHAT IS SOCIAL MEDIA BUDDY?

Social Media Buddy is an App/Platform that will enable users to mine our token automatically as they go about their daily social media use, the Crypto Currency (SMBC). and within 12 months our App will progress to be able to mine the top ten minable Cryptos such likes as BTC ETH LTC and Doge to mention a few as with SMB this will all be automatic with your social media use; our technology will have a very user-friendly interface which will be a simple matter of highlighting preferences and clicking next. The App will be available on both IOS and Android devices, once downloaded you will have the opportunity to add the most widely used social media accounts then each time users go about using the many different accounts they will be mining crypto currency that simply, any SMBC or other mined assets will go directly into the App wallet enabling users to monitor their profits all this generating an income without the purchase of expensive equipment and not to mention the Einstein intelligence to set it up.

## WHAT IS SMBT ?
The initial SMB will be an Erc20 token for ICO purposes only (SMBT) this will enable token sales and investors to track their investments. One priority function of the token will be to have a burn function, this functionality will allow all the supply of SMBT to be permanently eliminated once SMBC is completed and tradable this will be satisfied before the first listing. Investors will receive a One for one when the blockchain for SMBC is complete and the coin has full functionality as intended, the new Coin will be SMBC. All tokens withdrawn from the ICO website will automatically be SMBC and be fully tradable on the exchange. The SMBT will also be a safeguard against scammers as it will be useless on exchanges when we list on our first exchange. <br><br>
<p align="center">
<img style="width:100%; height: 200px" src="https://raw.githubusercontent.com/arif98741/smb/master/img/what-is-smbc.png">
</p>

## WHAT IS SMBC ?
SMBC will be our own crypto coin that functions on its own blockchain and have full mining capabilities that are only compatible with our Social Media Buddy App. This will be the Coin that investors will receive after the vesting periods (the details of which will be in our Tokenomics section), once the ICO is complete. As with all other coins this will be tradable on exchanges and all transactions will be traceable on the social media buddy blockchain.
<br>

**SMBC BLOCKCHAIN: POWERING A
DECENTRALIZED SOCIAL MINING FUTURE**

The SMBC project ushers in a new era of social media engagement with a custom-designed blockchain built for security, scalability, and fostering a thriving social mining ecosystem.

## TECHNICAL UNDERPINNINGS:
The SMBC blockchain leverages a robust consensus mechanism like Proof- of-Stake (PoS) to secure. the network and validate transactions. This mechanism ensures efficient operation by minimizing energy consumption compared to Proof-of-Work (PoW) models used by some blockchains.
Secure hashing algorithms like SHA-256 guarantee the immutability and integrity of data stored on the blockchain, ensuring a tamper-proof record of all SMBC transactions.

SMBC BLOCKCHAIN: <br>
A Deep Dive into Technical Architecture
This section delves deeper into the technical specifics of the SMBC blockchain, providing a more intricate understanding of its design and functionality.

CONSENSUS MECHANISM:
Delegated Proof-of-Stake (DPoS)
The SMBC blockchain utilizes a variant of Proof-of-Stake (PoS) called Delegated Proof-of-Stake (DPoS). In DPoS, token holders elect validators responsible for block creation and transaction validation. This approach offers significant energy savings compared to Proof-of-Work (PoW) while maintaining robust security.

SECURITY ANALYSIS:
* Byzantine Fault Tolerance (BFT): The DPoS protocol leverages a Byzantine Fault Tolerance (BFT) algorithm, such as PBFT (Practical Byzantine Fault Tolerance), which ensures network functionality even in the presence of malicious actors or network delays.
* Stake Weighting: Token holders delegate their stake to validators. The probability of a validator being selected for block creation is proportional to their delegated stake. This incentivizes validators to act honestly, as slashing penalties (loss of stake) exist for malicious behavior.

1. PREPARE PHASE: <br>
   A validator proposes a new block to other validators and broadcasts a PRE- PREPARE message containing the block data.
2. PRE-VOTE PHASE: <br>
   Validators validate the block and broadcast a PRE-VOTE message if they agree with the proposal.
3. COMMIT PHASE: <br>
   If a validator receives 2f + 1 PRE-VOTE messages (where f is the maximum number of Byzantine faults the system can tolerate), it broadcasts a COMMIT message for the block.
4. DECISION PHASE: <br>
Upon receiving 2f + 1 COMMIT messages, a validator finalizes the block and broadcasts a DONE message.

`Equation for Byzantine Fault Tolerance Threshold (f): f = (n - 1) / 3`

where n is the total number of validators in the network. This equation helps determine the system's resilience to Byzantine faults based on the number of validators. <br>
EQUATION FOR STAKE WEIGHTING: <br>
Validator Selection Probability (Vi) = Stake Delegated to Vi (Si) / Total Delegated Stake (∑Sj)

SCALABILITY SOLUTIONS: <br>

The SMBC blockchain anticipates future growth and explores two potential scaling solutions:
1. Sharding: The network can be partitioned into horizontal shards, each processing a subset of transactions. This distributes the workload, improving transaction throughput.
   * State Sharding: This approach shards the entire blockchain state, requiring communication between shards for specific transactions. 
   * Transaction Sharding: Only transactions are sharded, with the complete state maintained on all shards. This simplifies cross-shard communication but may require additional storage space.
2. Sidechains: These are separate blockchains that interact with the main SMBC blockchain. They can offload specific functionalities, reducing congestion on the main chain. Security bridges ensure secure asset transfer between the main chain and sidechains.

SOCIAL MEDIA MINING ALGORITHM
The SMBC platform employs a custom algorithm to reward user engagement and incentivize positive social media behavior. The algorithm considers various metrics to determine mining rewards:
* Content Quality Score (CQS): This metric evaluates the quality and originality of user-generated content using natural language processing (NLP) techniques and sentiment analysis.
* User Engagement Score (UES): This score considers factors like likes, comments, and shares to gauge user interaction with content.
* Time Spent on Platform (TSP): Rewarding users for active participation by factoring in the total time spent on the Social Media Buddy App.

**Weighted Mining Reward Calculation:** <br>
Mining Reward (MRi) = α * CQS (Ci) + β * UES (Ui) + γ * TSP (Ti) + ω * Category Weight (CWj) where ω is a weighting factor and CWj represents the weight assigned to a specific content category (e.g., educational content, creative content). <br> <br>
<p align="center">
<img style="display: block; width:70%; height: 200px" src="https://raw.githubusercontent.com/arif98741/smb/master/img/weighted-minining-reward-calculation.png">
</p>


**Data Storage and Security:**
* InterPlanetary File System (IPFS): To optimize storage efficiency and data availability, the SMBC platform can leverage IPFS for decentralized storage of non-critical data like user profiles and media content.
* Secure Enclaves: Sensitive user data can be stored within secure enclaves (hardware or software-based) on user devices, adding an extra layer of security.

**Security Audits:** <br>
Regular security audits conducted by independent security firms will be implemented to identify and address potential vulnerabilities in the SMBC blockchain and smart contracts.

**Solidity Smart Contracts:**
The Engine of Automation Solidity smart contracts, self-executing code stored on the blockchain, act as the engine that automates crucial functionalities within the SMBC ecosystem. These programmable scripts offer several key advantages:

* Transparent and Secure Token Management: Smart contracts will govern the distribution and vesting schedule of SMBC tokens as outlined in the Tokenomics section. This ensures a transparent and immutable process, fostering trust among investors and users.
* Dynamic Social Media Mining: Smart contracts will establish the foundation for social media mining within the Social Media Buddy App. They can be programmed to reward users based on a variety of engagement metrics. For instance, users might receive higher rewards for high-quality content creation, fostering a more positive and valuable social media experience.
* Frictionless Transactions: Smart contracts facilitate secure and peer-to- peer transactions between users within the Social Media Buddy App. This eliminates the need for intermediaries, reduces transaction fees, and empowers users with greater control over their crypto assets.

**Scalability for Future Growth:**
The SMBC blockchain is designed with scalability in mind to accommodate a burgeoning user base and transaction volume. The development team is actively exploring potential scaling solutions like sharding or sidechains to ensure the network can efficiently handle future growth. <br>

The SMBC blockchain is designed with scalability in mind to accommodate a burgeoning user base and transaction volume. The development team is actively exploring potential scaling solutions like sharding
or sidechains to ensure the network can efficiently handle future growth.

<p align="center">
<img style="display: block; width:70%; height: 200px" src="https://raw.githubusercontent.com/arif98741/smb/master/img/graph-1.png">
</p>

<br><br>
<p align="center" style="font-size: 20px; margin-top: 30px; color: red;">BEYOND SMBC: A</p>
<p align="center" style="font-size: 20px; margin-top: 30px; color: red;">MULTI-COIN FUTURE
</p>

The SMBC blockchain isn't limited to just SMBC tokens. The future roadmap envisions expanding
mining capabilities to include top cryptocurrencies like Bitcoin, Ethereum, Litecoin, and Dogecoin within
12 months. This paves the way for a diverse and dynamic crypto mining experience directly integrated
with social media engagement. Transparency at Your Fingertips
All SMBC transactions and mined assets are permanently recorded on the SMBC blockchain, providing
complete transparency and auditability. Users can leverage the Social Media Buddy App to monitor
their mining activity, track their SMBC and potentially other mined crypto holdings, and manage their
entire crypto portfolio conveniently and securely. Building a Secure and Sustainable Future
The SMBC blockchain prioritizes both security and sustainability. The chosen consensus mechanism
(e.g., PoS) offers a more energy-efficient alternative to PoWmodels, contributing to a more sustainable
future for blockchain technology


## <p style="align: center; text-align: center;"><span style="color: red;">PROBLEM<span></p>
<p align="center">
<img style="display: block; width:80%;" src="https://raw.githubusercontent.com/arif98741/smb/master/img/problem-image.png">
</p>

In a world where digital technology primarily Blockchain closely coupled with Crypto Currency which include Tokens and Coins many cryptos have a mining functionality Mining is the process by which networks of specialized computers generate and release new Crypto Currency and verify new transactions. Mining is the process that Bitcoin and several other cryptocurrencies use to generate new coins and verify new transactions. It involves vast, decentralized networks of computers around the world that verify and secure blockchains – the virtual ledgers that document cryptocurrency transactions. In return for contributing their processing power, computers on the network are rewarded with new coins. It’s a virtuous circle: the miners maintain and secure the blockchain, the blockchain awards the coins, the coins provide an incentive for the miners to maintain the blockchain, delivering the ability for people to increase wealth for themselves. Blockchain is becoming adopted at a rate no other tech has previously accomplished yet people from nations worldwide trail behind when it comes to accepting, understanding, and embracing new concepts.
Even though major corporations have already started to implement it into everyday living. We understand that fear and our in-built human scepticism often play a major role in widespread understanding and acceptance. As with anything new, a lack of clear information, easy to understand material and user-friendly Apps or Platforms add to the slow uptake of global adoption.
We do not always need to know the intricate workings or dynamics of technologies so long as we get easy to use products that deliver results that Favor ourselves and help us to prosper many people the world over would be involved in Crypto and its many connected technologies if they had easy to use Apps and Platforms. Mining crypto usually involves buying expensive hardware and software then having to take time to learn how to setup the equipment to start mining crypto currency to prosper.

<br>
Social Media Buddy believes we have a solution to help citizens from every continent to prosper from Crypto Currency mining and Blockchain using a simple app.

## <p style="align: center; text-align: center;"><span style="color: red;">SOLUTION<span></p>
<p style="width: 80%; text-align: left">
What if an app/platform was available that made it simple to generate income just by using your everyday social media platforms, many of you reading this document will already have a good understanding of Crypto and its many coupled resources. Our App/Platform will simply connect to the most wide spread social media platforms like Instagram,Tiktok,Youtube,Facebook etc and begin to mine our Token generating wealth for Social Media Content Creators and Social media users alike and with the App/Platform being available for IOS and Android everyone will have a simple extremely cost effective way to prosper. Our app will not only mine our native token it will also be able to mine many other minable tokens and coins within the crypto market.

</p>

## OPPORTUNITY
<p>
Since the public launch of Facebook in 2006 the world has seen a rapid expansion in social media platforms reaching billions of people around the world who have an endless thirst for engaging on each and every one of them. Over 60% of the world population now uses social media, approximately 5 billion people with well over 250 million new users coming on board last year, amazingly the average time spent using social media per day is over 2 hours per person. Now we know the approximate figures of the popularity its easy to understand how billions of dollars are made every year by platform owners and companies who choose to use these services to advertise. Millions of people create content as a means of providing an income and for many content creators this is their only means of making a salary. Social Media Buddy believes that a monumental opportunity to combine Crypto Currency, Blockchain and A.I in a ground breaking new App mining an array of available cryptos including our very own coin (SMBC) just by engaging on social media platforms which more than half the global population does daily anyway can be the stand out project of 2024.

</p> <br>
<p style="width: 70%;">
The app will be available for user to purchase for a small fee from the relevant platforms their service providers provide for application downloads. The income from the sales of the app will take pressure off our native token allowing SMBT to increase in value steadily as Social Media Buddy will not need to release tokens to raise revenue for future development, the funds generated from the app sales will cover day to day running and any further company growth protecting SMBC price saving investors from footing the cost as coin release usually has a negative impact on coin price.
</p>

## TOKENOMICS
<p align="center">
<img style="display: block; width:80%;" src="https://raw.githubusercontent.com/arif98741/smb/master/img/social-media-text.png">
</p>

## SALES ROUNDS
<p align="center">
<img style="display: block; width:80%;" src="https://raw.githubusercontent.com/arif98741/smb/master/img/sales-round.png">
</p>


## ICO

<p align="center">
<img style="display: block; width:80%;" src="https://raw.githubusercontent.com/arif98741/smb/master/img/ico.png">
</p>

<p align="center">
<img style="display: block; width:80%;" src="https://raw.githubusercontent.com/arif98741/smb/master/img/token-distribution.png">
</p>

## ACCEPTED PAYMENTS
<p align="center">
<img style="display: block; width:80%;" src="https://raw.githubusercontent.com/arif98741/smb/master/img/accepted-payments.png">
</p>

<br>
<br>
<br>
<p align="center">TOKEN DETAILS SMBT
Token Standard ERC20<br>
Token Ticker SMBT<br>
Blockchain Ethereum</p>

## OUR BUY BACK POLICY
To fuel the success of SMB we are reinvesting part of the blockchain fees as buybacks, wherein we buy and then burn the crypto assets, in return lowering the SMB total supply and growing the market cap overall. A percentage of the fees are used as an inventory, the inventory buyback happens whilst SMB buys back the coin at the current market price and absorbs them, reducing the total quantity of coins available on the open market. <br><br>
The two successful tools are buybacks and burns. And at the same time as each of these techniques essentially accomplish the equal intention, this mechanism reflects a victory for the financial model for the investors of SMBC while also protecting from the market’s volatility and providing the catapult effect, continuously fuelling the buybacks to increase the coins' demand and valuation 

<br><br>

<p align="center">Mine⚙Supply⚙Demand⚙Transaction⚙Buyback</p>


