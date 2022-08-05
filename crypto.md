# Virtual Currency

## CONTENTS

- Intro: Terms & Concepts: [`Miscellany`](#miscellany), [`Money`](#money), [`Fiat Currency`](#fiat-currency), [`Virtual Currency`](#virtual-currency), [`Tokens`](tokens), [`Stable Coins`](#stable-coins), [`Currency Exchanges`](#currency-exchanges)

- Blockchains: [`Decentralized, Peer-to-Peer Network`](#decentralized-peer-to-peer-network), [`Blockchain Blocks`](#Blockchain-Blocks), [`Blockchain Growth`](#Blockchain-Growth)

- Mining: [`Definition`](#definition), [`Miners`](#miners), [`Mining Tools`](#mining-tools), [`Tracing & Tracking`](#tracing--Tracking)

- Bitcoin: [`Terms`](#terms), [`Definition & Description`](#definition--description), [`Bitcoin Address`](#bitcoin-address), [`Private Key`](#private-key), [`Wallets`](#wallets), [`Bitcoin: How It Works`](#bitcoin-how-it-works), [`Bitcoin: Mining`](#bitcoin-mining), [`Bitcoin: Explorers`](#bitcoin-explorers)

- Ethereum: [`Ethereum: Wallet Types`](#ethereum-wallet-types), [`Ethereum: Address Types`](#ethereum-address-types), [`Ethereum: Transactions`](#ethereum-transactions), [`Ethereum: Smart Contracts`](#ethereum-smart-contracts), [`Ethereum: The EVM`](#ethereum-the-evm), [`Ethereum: Distributed Apps`](#ethereum-distributed-apps), [`Ethereum: DeFi`](#ethereum-defi), [`Ethereum: DEX`](#ethereum-dex), [`Ethereum: Yield Farming`](#ethereum-yield-farming), [`Ethereum: Mining`](#ethereum-mining) 

- NFTs (Non-Fungible Tokens), 
[`Definition & Description`](#definition--description), [`Money Laundering`](#money-laundering), [`Rarible`](#rarible)

- Stable Coins
[`Purpose`](#purpose), 
[`Examples`](#examples)

- Privacy Coins: Monero
[`Stealth Address (recipient)`](#stealth-address-recipient), [`Ring Signature (sender)`](#ring-signature-sender), [`RingCT (transaction)`](#ringct-transaction), [`Mining`](#mining)

- Tracing Techniques
[`Documentation`](#documentation), [`Screenshots`](#screenshots), [`Screen Recorders`](#screen-recorders), [`Hunchly `](#hunchly), [`Step 1: Identify Keys`](#step-1-identify-keys), [`Step 2: Trace Transactions`](#step-2-trace-transactions)

- Links & Resources
[`Start Here`](#launching-pad), 
[`BitCoin Terms`](#bitcoin-terms), 
[`Explorers, BitCoin`](#explorers-bitcoin), 
[`Explorers, Ethereum`](#explorers-ethereum), 
[`Explorers, Other`](#explorers-other), 
[`Exchanges`](#exchanges), 
[`BitCoin ATMs `](#bitcoin-atms), 
[`NFTs`](#nfts), 
[`Trackers`](#trackers), 
[`Crypto Abuse`](#crypto-abuse), 
[`Visualization`](#visualization)

## Intro: Terms & Concepts

### Miscellany

- **Book:** American Kingpin by Nick Bilton
- **Note:** Bitcoin is traceable, and anonymity can be broken.

[`top`](#Virtual-Currency)

### Money

- Defined (wikipedia): legal tender in a country (and crypto is not that, yet)
- Key Components for Money to be Money:
  1. Medium of Exchange: to be able to compare values of dissimilar objects.
  2. Unit of Account: money acts as a standard of measure--a common denomination of trade
  3. Store of Value: it can be saved, retrieved, and exchanged at a later time; predictable

[`top`](#Virtual-Currency)

### Fiat Currency

- Currency without intrinsic value that is established as money, often by government regulation. Assigned a value... exchanging parties agree to its value...

### Virtual Currency

- A medium of exchange that operates like a currency in some environments, but does not have all the attributes of real currency. In particular, virtual currency does not have legal tender status in any jurisdiction (except in El Salvador).

**Convertible Virtual Currency:** open currency, can be exchanged back and forth for real fiat currency (e.g., Monero, Bitcoin, Dash, DogeCoin, LiteCoint, Etherium)

**Non-Convertible Virtual Currency:** closed currency, cannot be exchanged into fiat currency (e.g., rewards cards/programs, video game currency); designed to be used within a closed program (like Marriot, airlines reward system; you can "spend" the currency in that closed environment).

**Centralized:** Currency that has a single administrative authority (one entity controlling the system)

**Decentralized:** Currency that does not have any central authority (crypto currency; open-source; peer-to-peer currency; math-based)
- Therefore, "crypto-currency" is decentralized because it is math based).

[`top`](#Virtual-Currency)

### Tokens

- Crypto tokens are cryptocurrency tokens. Cryptocurrencies or virtual currencies are denominated into these tokens, which reside on their own blockchains.
- Crypto coins have their own network
- Tokens reside on a particular platform or existing blockchain

**Note:** A "token" often refers to any cryptocurrency besides Bitcoin and Ethereum (even though they are also technically tokens). Because Bitcoin and Ethereum are by far the biggest two cryptocurrencies, it's useful to have a word to describe the universe of other coins.

**Category #1:** Utility Tokens: unregulated and high risk of scam

**Category #2:** Security Tokens: heavily regulate, value tied to a company itself

[`top`](#Virtual-Currency)

### Stable Coins

A subset of cryptocurrency, attempts to offer stability
- USD Coin, Dai, Tether, TrueUSD, Gemini Dollar
- Backed by Crypto, Commodity, Fiat, or a combo
- **PROS:** borderless, fast, public ledger system
- **CONS:** centralized, audios, lower ROI growth

[`top`](#Virtual-Currency)

### Currency Exchanges

Online platforms to exchange one currency to another, and to fiat also
- CoinBase (be familiar with this; sign up to see how it works)
- BitStamp (based in UK)
- Binance.com (French-based); Binance.US

[`top`](#Virtual-Currency)

----

## Blockchains

[Blockchain Demo](https://andersbrownworth.com/blockchain/): short videos, overview

The "blockchain" is the "ledger" for all the transactions with the currency.
- Need 51% of all copies of the ledger to agree for a transaction to be accepted.

In 2008, with the onset of the financial crisis (housing bubble), BitCoin comes on the scene and it's "ledger" (the blockchain) eliminated the need to go through a centralized authority to pay for stuff.
- **Centralized:** one central governing authority
- **Decentralized:** multiple authorities working in conjunction
- **Peer-to-Peer:** no centralized authority whatsoever

[`top`](#Virtual-Currency)

### Decentralized, Peer-to-Peer Network

- Network of peer-to-peer nodes. Anyone can run a node. Participation is voluntary
- Node Numbers: In March of 2021) there were about 10,000 Bitcoin blockchain nodes in existence
- Each node maintains a full copy of the distributed ledger (remains sychronized)
- Contains list of all transactions on the network
- Prior to being added to a block, transactions are said to be "unconfirmed"
- Size matters (as transaction, wallets, etc. are added to the blockchain, it grows... and grows):
  - The current BitCoin blockchain is about 250GB
  - The current Ethereum blockchain is about 1TB

[`top`](#Virtual-Currency)

### Blockchain Blocks

The "blocks" of a blockchain consist of:
1. Header (metadata, hash values, etc.)
2. Data (list of transactions)
   - Data is hashed and the value is added to the block's header; and then...
   - That hash value is added to the next block's header to "chain" each block with the subsequent
   - This is the protection against data manipulation.

[`top`](#Virtual-Currency)

### Blockchain Growth

The original Bitcoin blockchain has been altered and adapted for newer digital currencies.

**Smart Contracts:** became popular with Etherium
- Uses blockchain technology to execute distributed code (computer programs), known as smart contracts
- Used for: games, digital collectibles (NFTs), ERC-20 Tokens, Resource Sharing

**Decentralized Finance (DEFI): ** Financial services on public blockchains. Do whatever you could with traditional financial services like banks, etc. but decentralized (and therefore "free market").

**Supply Chain:** blockchain technology can be used to...
- Track products from production to consumer: produce, pharmaceuticals, gems, etc.
- Verify sourse: farm, mine, manufacturer
- Can cut tracing time down from weeks/days to seconds
- Information could be accessible to the public
- Track and verify ownership: art, real estate, intellectual property
- Identify and protect the creators of the works
- Track the sale and transfer of property
- ID management. Hospitality management. Loyalty programs. Cross-border payments. Elections.

[`top`](#Virtual-Currency)

----

## Mining

### Definition

"Mining" refers to the process of verifying and adding transactions to the blockchain. 

There are two main protocols (algorithms) of mining--two types of mining: 

1. **Proof of Work (PoW):** high energy usage; hardware requirements; original method
   - Verify unconfirmed transactions (a competitive process)
   - Add verified transactions to a new block
   - Solve the Proof of Work mathematical problem
   - The miner who solved the math problem first was rewarded for the work (he "mined" some coin).
   - PoW is a competitive race in which participants (miners) expend computational energy in order to validate transactions and propose valid blocks.
   - In order to create a new block, miners on a PoW network compete against each other to solve complex mathematical problems in a process called hashing. These puzzles are very hard to solve, but should be easy for the network to verify the correct solution. 
   - Bitcoin, Ethereum (moving to a proof-of-stake), Litecoin, Monero, Dash

2. **Proof of Stake (PoS):** low energy, no hardware necessary; e.g., Tezos, Atom, Algoran
   - Staking locks cryptocurrency: once it's staked, it cannot be transacted until removed from Staking
   - Verify unconfirmed transactions
   - Selection is random from all staked miners... (??)
   - PoS is a modification of PoW introduced in 2012 as a means to solve its perceived dependency on energy consumption as a means to determine blockchain ordering.
   - The PoS algorithm pseudo-randomly elects a node (anyone who owns the coin) to propose the next block to the blockchain. When a node gets elected, its role is to verify the validity of the transactions within the block, sign it and propose the block to the network for validation.
   - It's basically a "lottery" system instead of a competition.
   
**More on Proof of Stake (PoS) Mining:**

"Staking" refers to a "buy in" amount (of the crytpo on your particular blockchain) required to participate in the transaction and block validation process (to participate in the "lottery"). Your crypto is still yours, but it's "locked" in the "stake" (like you "lock" your money in a certificate of deposit). The idea is, your stake amount of crypto is an "investment" you're making to earn interest (to earn rewards in the mining "lottery").
- Staking locks cryptocurrency. Once it is "staked," it cannot be transacted until removed from Staking.
- Staking my occur directly from a wallet or via pool.
- Stakeable exchanges: Binance, Coinbase, etc.

In the PoS algorithm, a miner is chosen at random from all those who have "staked" a claim to participate in the "lottery."
- A miner's chance of being selected proportional to the amount of crypto staked. Stake more of your crypto ("invest" more of your "money") and you get a higher probability of getting picked (return on investment).
- Therefore, one could think of each "stake" like a lottery ticket: the more stakes you have (the more crypto you invest/stake), the greater chance you have of being selected and "mining" the reward.

Because of this, solo staking is prohibitive for the little guys so they pool mine. It's a "cost of entrance" or a "buy-in price." This is why "mining pools" are so popular (see below).
- You have to hold a certain amount of the crypto currency before you can stake. 
- You still have to have a rig that can do so many hashes per second. 
- But, once you're staked, you're staked. Can't lose it unless you do nefarious things and get booted.

**Example:** Tezos network is PoS.

**Delegating:** similar to pool mining... to avoid the prohibitive buy-in cost.

[`top`](#Virtual-Currency)

### Miners

**Solo Mining:** Miner works alone to solve the cryptographic puzzle.
- Requires a massive investment in hardware
- All rewards are given to a single miner (you).
- Can take you minutes or years to solve the math problem, depending on your equipment

**Mining Pools:** Groups of individuals/entities working together to solve the math problem (and then split the reward should they validate the block).
- "Workers": devices (mining installs), computers running the mining software of the group.
- "Share" ("last share"): partial cryptographic solutions submitted periodically to prove you are working on the problem. When your shares drop below a certain number, you are shown to be offline.
- "Block Reward": the amount the miner received for the "work" his machine is doing

**Hashrate:** Miners (based on their equipment) are rated with a "hashrate"--kind of like the "horsepower" your hardware has. It measures the amount of work being performed.
- The higher the hashrate, the more math you can do.
- The total hashrate is the hashrate of all workers
- Measurements: Current = Active (now); Average = over time (should be close to your current)

[`top`](#Virtual-Currency)

### Mining Tools

**Mining Software:** Multiple mining applications; some examples from Ethereum...
- T-Rex
- Team Red Miner
- Phoenix Miner
- Eth Miner

**Mining Manager:** [Awesome Miner](https://www.awesomeminer.com/)
- "All in one" utility giving you granular control over mining processes.

[`top`](#Virtual-Currency)

### Tracing & Tracking

Mining pools will contain data on the miners and their activities. How much data is available depends on the pool and how it's structured. 

Many mining pools require nothing more than a (crypto currency) wallet address.
  
Historical data is searchable by that address:
- Rewards (total earned)
- Payments (total sent to wallet)
- Balance
- Workers
- Hashrate Hitory

You may be able to trace and track in order to serve process and obtain identifiable data?
- IP Addresses
- Notification email addresses (submitted by miner for notifications, etc.)

Some mining pools require account creations (Slushpool, BTC.com; lots of BitCoin pools). In order to participate in the mining pool, you have to create an account and provide some of your personal info: 
- All your data is kept in your account (which can be hacked, subpoenaed, etc.)
- Could we serve process and obtain identifiable data?
  - IP Addresses
  - Notification Email Addresses
  - Payment addresses

[`top`](#Virtual-Currency)

----

## Bitcoin

### Terms

**BitCoin Address (public key):** the alphanumeric address to which funds are sent; similar to an email address (unique identifying number).

**Private Key:** Used to sign transactions and provides the ability to spend associated bitcoin; public/private keys are generated in pairs.

**Wallet:** Software that manages keys and is used to transfer bitcoin; analogous to a physical wallet. It holds your private/public key pairs. A wallet can hold more than one address.

**Transaction:** A message propagated on the network that identifies the transfer of bitcoins from the owner to the recipient.

**Confirmation:** A transaction which has been verified and added to a block on the blockchain.

**Block:** A group of transactions that have been confirmed and added to the blockchain.

**Blockchain:** Public, chronological, digital ledger of transactions

**Mining:** The process of verifying transactions and adding blocks to the blockchain.

**Tumbling (mixing):** A process to try to obscure the source and destination of transactions; a form of bitcoin "laundering"

**BTC:** The common abbreviation used to identify a value in Bitcoin; i.e., USD, EUR, GBP, etc.

[`top`](#Virtual-Currency)

### Definition & Description

Bitcoin is a decentralized, peer-to-peer, blockchain-based cryptocurrency.
- First block added in January of 2009
- It is NOT anonymous. It is pseudo-anonymous. 

Bitcoin is limited: 21 million bitcoins (20,999,999.9769)
- New bitcoin created every 10 minutes (one new block created)
- Last bitcoin will be "minted" in the year 2140

Bitcoin can be divided up to 8 decimal places: .000 000 01 BTC
- It's lowest denominator known as a satoshi.

[`top`](#Virtual-Currency)

### Bitcoin Address

This is your public key that you provide to others to send you money. 
- Alphanumeric value used as the destination of a bitcoin transaction
- Will start with a 1, 3, or bc1
- Can also be represented by a QR Code (make sure you get this on your search warrant)

**Various Types of Bitcoin Addresses:**
- P2PKH  (alias: Legacy) - Starts with 1   [used only one private/public key pair; single]
- P2SH   (alias: Segwit) - Starts with 3   [Segregated Witnesses; Multi-Sig Address]
- P2WPKH (alias: Bech32) - Starts with bc1
- P2WPH  (alias: Bech32) - Starts with bc1

[`top`](#Virtual-Currency)

### Private Key

Your private key (of the private/public key pair) is your "secret value."
- It is needed to sign transactions and spend bitcoin (it is your "digital signature").
- It is a 256-bit number (can be displayed in a variety of ways)
- It is mathematically related to a public key.

[`top`](#Virtual-Currency)

### Wallets

A Bitcoin wallet is software that provides access to the Bitcoin network/blockchain.
- The wallet willl generate and hold the keys (public and private) associated with an account
- The wallet is used to initiate transfers and sign transactions
- The wallet tracks the total account balance for all keys kept by that wallet. 

**There are four wallet types:**
1. Non-Deterministic Wallet: maintains randomly generated keys
2. Deterministic Wallet: uses a seed phrase to generate keys
3. Full Node Wallet: Downloads and maintains a complete copy of the blockchain
4. Partial/Lite Node Wallet: like a full-node, but only downloads part of the blockchain

**There are two wallet formats** (referred to as "Wallet Import Formats" [WIFs]). You can tell which is which by the starting character.
1. **WIF - Uncompressed Pubkey:** starts with 5
2. **WIF - Compressed Pubkey:** starts with K or L

Wallets are important if you want to seize Bitcoin. In order to seize Bitcoin, you have to have one of two things: 
1. You must have EACH PRIVATE key the perp used to obtain his Bitcoin (each transaction could have been conducted with a different wallet address).
2. Or you have to the **mnemonic seed phrase** that will get you into his wallet (which will have all his private keys).

**Mnemonic Seed Phrase:** A list of words created by a deterministic wallet (usually about 12)
- Used to backup or recover the public/private key pairs kept in a wallet.
- Therefore, a mnemonic seed phrase can be used to get into an entire wallet (with an innumerable amount of addresses--public/private keys).

**NOTE:** So, if you are searching a residence, vehicle, digital device, etc., pay attention to a string of random words jotted down on a piece of paper.

**There are five wallet platforms:**

**1. Desktop Wallets:**
- These are applications installed and run from a computer (full or lite nodes).
- Keys are stored locally on the machine (with access to the app, they can access your stuff)
- Potential Dangers: hacking, malware, hardware failure--could lose everything.
- Owner responsible for backing up keys to prevent loss

**2. Mobile Wallets:**
- These are apps installed and run on phones or tables (usually lite/partial nodes)
- Keys stored locally on the mobile device.
- Shares the same security and dangers as a desktop wallet (increased danger of being lost or stolen).

**3. Web (Online) Wallets:**
- Keys are stored and maintained by online third-party service.
- Accessed through a mobile app or a browser.
- Allows access from anywhere any time.
- Trust must be given to the third-party to maintain keys.
- Most exchanges also offer a web-based wallet.

**4. Hardware Wallet:**
- These are dedicated (physical) devices designed to secure and maintain keys
- Typically compatible with multiple cryptocurrencies
- Device must be connected to a computer to transfer funds; works in conjunction with a desktop or mobile wallet.
- Falls under the category of cold storage (keys not stored on 'online')
- Transactions occur on the blockchain and when you plug in your hardware wallet, it updates.
  - You can receive funds all day long but you have to be connected to send funds.
  - Your crypto is "kept" on the physical device--in the hardware wallet. 
- Perps would have to steal your physical device AND get your PIN to access it.
- The manufacturer will let you provide a seed phrase to access the wallet in case you lost your PIN, etc.
- Brands: [Ledger](https://www.ledger.com/), [KeepKey](https://shapeshift.com/keepkey), [Trezor](https://trezor.io/)

**5. Paper Wallets:**
- This is just a piece of paper (seriously)
- Public and private keys printed out (or represented by QR codes)
- This is also "cold storage"

[`top`](#Virtual-Currency)

----

## Bitcoin: How It Works

Incoming transactions are called **INPUTS**.
- Your "balance" will be the sum of your **unspent** inputs/transactions

Outgoing transactions are called **OUTPUTS**.
- When you send Bitcoin to another wallet, your **inputs** are spent.

**Each INPUT functions like a BILL of CURRENCY.**
- When you see input transactions listed, each having a certain amount of Bitcoin you received, you are seeing the "bills of currency" you can "spend."
- You must use the WHOLE INPUT just as you would use a bill of currency. And you can only use it one time.
- If you spend LESS than the INPUT, you get another (new) input for the "change" (an additional output, along with what you "spent/sent"). This way inputs and outputs are EQUAL, but then you would receive an input for the "change."
- When you spend it, the wallet uses the least number of inputs for the transaction
- If you combine inputs to make one (larger) output, the two inputs are shredded and the total becomes one input for the recipient.

[`top`](#Virtual-Currency)

----

## Bitcoin: Mining

"Mining" refers to the transaction verification process:
1. Confirm transaction signed by sender
2. Confirm bitcoins have not been spent
3. Adds blocks to the blockchain as they fill up and the crypto math problem is solved by the miners.

New Bitcoins awarded to the miner of the block
- Originally 50 new Bitcoins were "minted" per block a miner added to the blockchain.
- Every 210,000 blocks, the number of bitcoin created is halved.
- Currently: 6.25 new bitcoin "minted" per block

New blocks are minted approximately every 10 minutes (on average).
- That's the goal: one block every 10 minutes. The blockchain will make adjustments to make that ten-minute window.
- The network (blockchain) keeps track of the number of blocks. If the number goes up (taking less than 10 minutes to solve the math problem and add a new block), the network changes the cryptographic problem to make it take longer. If the no one is getting the answer, too much time... then the network makes the cryptographic problem easier to speed things up.
- This way they network maintains the average time of each block to be about every 10 minutes.

The blockchain makes the adjustment using a variable "Difficulty Level."
- This adjustment is made approximately every two weeks.

**Difficulty Estimator:** https://www.bitrawr.com/difficulty-estimator

[`top`](#Virtual-Currency)

----

## Bitcoin: Explorers

"Explorers" are used to exploring, look at, analyze, and trace transaction through the blockchain.

**Two Favorite BitCoin Explorers:**
1. BlockChair: https://blockchair.com/  (based in Romania; may have firewall issues getting there)
2. BlockChain: https://www.blockchain.com/explorer

**How to Read the Explorer Output:**
- Transactions are listed in a "stack" (the first on the bottom, the last on the top).
- The "top" transaction of every block (the last transaction) is the reward the miner of the block received.
  - This may help you ID the miner, if you would be so inclined.
- This reward transaction shows the "Sender" as "Coinbase." That is the name of the origin of the Bitcoin, NOT the exchange called "Coinbase" (they stole the name for marketing purposes).
- Coinbase = Newly Generated Coins

**The Blockchain Can Fork:**
- [Example](https://www.blockchain.com/en/search?search=8e945c4b34457076bec817a30ed2cf3feed720937f4fb7f40b4d96438e44dcf6)
- When there is a disagreement among nodes that cannot be resolved, the blockchain forks and a new currency is created. In the above example, BCH was born from the fork: 
  - Original: BTC (Bitcoin)
  - Fork:     BCH (Bitcoin Cash)

**Pay Attention to the "Change":**
- Because change goes back to the SAME WALLET, you can tie in two addresses into the same perp's wallet.
- If there is change in a transaction, you have the input address(es) AND the output address for the change (because the change goes back to the guy who paid with his inputs; so you know he controls this address also).

**Clustering:**
- Co-spending can ONLY come from ONE wallet. Two or more addresses in the input are the SAME wallet.
- Therefore when you see two (or more) addresses used to send funds, you can assume the ALL those input addresses are controlled by the same wallet (i.e., the same perp).
- And you can thereby associate more Bitcoin addresses with the perp to trace him and track him.

[`top`](#Virtual-Currency)

----

## Ethereum

**Explorer of Choice:** etherscan.io

Ethereum is a decentralized, blockchain-based, distributed application platform (and it's not just "online cash").
- Turing complete programming platform
- Allows for self-executing, immutable smart contracts (computer code triggered like a "logic bomb").

Unlike bitcoin, Ethereum is NOT designed to be an "electronic cash system."

**Terms:**
- Ethereum  is the network.
- Ether     is the cryptocurrency or network token.

Ethereum was proposed in late 2013 by Vitalik Buterin as a next generation smart contract & decentralized application platform. 

Ether initial coin offering (ICO) in July 2014.
- 2,000 ether per bitcoin (declining to 1337)
- about $0.30 to $0.35 per ether
- about 60 million ether were sold during the ICO

Ethereum went live in July of 2015 (about 72 million coins premined).

Ethereum's cryptocurrency token, represented by ETH
- Can be divided into smaller units knowns was a wei
- 1,000,000,000,000,000,000 wei = 1 ETH   (one quintillion)
- Used to pay transaction fees (gas)
- Can also be "traded" like Bitcoin

[`top`](#Virtual-Currency)

----
## Ethereum: Wallet Types

Wallets are also called "clients" or "nodes." They are applications (software) that provide access to the Ethereum network.
- A wallet will hold the keys associated with an account/user.
- A wallet is used to initiate transactions.

[`top`](#Virtual-Currency)

### Wallet Categories
Wallets can be grouped into two categories:
**1. Full Node:** maintains full copy of the blockchain; requires significant computer recourses.
- validates all transactions (no third-party required); more difficult to use
**2. Lite Node:** Partial copy of the blockchain, less resources
- relies on third-party transaction verification; easier.

[`top`](#Virtual-Currency)

### Wallet Types:
**1. Desktop Wallets:** Can be partial or lite; MetaMask, Atomic Wallet, Exodus, Parity Ethereum, et al. Referred to as a "hot" wallet (attached to the network, live).
**2. Mobile Wallets:** Installed and run on phone or tablet, iOS or Android. Lite nodes; Jaxx Liberty, Coinomi, Trust Wallet. Also a hot wallet. 
**3. Web/Online Wallets:** Web sites/apps, wallet stored and maintained by online entity MyEtherWallet, MyCrypto, coinbase, Kraken, Bittrex. Another hot wallet.
**4. Hardware Wallets:** Piece of hardware, looks like a usb device; Ledger, Trezor, keepkey. Referred to as a "cold" wallet (the hardware/physical device must be connected to transfer funds)
**5. Paper Wallets:** A piece of paper; keys (public and private) printed on the paper can include a QR code to scan. Also referred to as a cold wallet (because you gotta get online to trade, etc.).

[`top`](#Virtual-Currency)

----

## Ethereum: Address Types

Ethereum addresses are also called accounts.

### Account Types
Ethereum has two types of accounts (two types of addresses):
**1. Externally Owned Account/Address (EOA) - owned by a person**
- Controlled by a private key
- Has an ether balance
- Can send and receive ether
- Can create and trigger smart contracts
**2. Contract Account/Address (CA) - owned and controlled by "code"**
- NOT controlled by a private key
- Controlled by the code of the smart contract
- Has an ether balance
- Received transactions trigger the contract's code

[`top`](#Virtual-Currency)

----

## Ethereum: Transactions

### Anatomy of a Transaction
- Nonce: ("Number used ONCE") Sequential number; generated by the sender (your first transaction is 0, the second is 1, the third is 2, etc.)
- Gas Price: price sender is willing to pay per unit of gas
- Gas Limit: total amount of gas sender is willing to pay
- Recipient: Ethereum destination address
- Value: amount of eth sent to destination address (can be zero value transactions that cause a trigger to happen)
- v,r,s: digital signature of the sender (cryptography; signed public keys, etc.)
- Init: code to initiate a contract
- Data: variable data payload (eth, message, data, etc.)

[`top`](#Virtual-Currency)

### Transaction Types (Funds Transfers)
1. Funds Transfer (similar to bitcoint): eth from sender to recipient.
2. Creating a Contract Account (Smart Contract): a transaction in which you create a contract (address created)
3. Trigger a Contract Account: a transaction that... triggers a smart contract (the program runs).

[`top`](#Virtual-Currency)

----

## Ethereum: Smart Contracts

"Smart Contracts" are just computer programs that run on the Ethereum Network.
- Executed by the Ethereum Virtual Machine (EVM)

Once initiated, the code in the smart contract is immutable (it cannot be changed).

The outcome is deterministic (it is the same execution for everyone).

Smart contract code is only run when triggered by a transaction from an EOA (Externally Owned Account/Address - owned by a person).
- They never "run on their own" or "in the background."
- Smart contracts cannot be triggered from another smart contract.

Smart contract code is written in a high-level language.
- [Solidity](https://docs.soliditylang.org/en/v0.8.15/) is the most frequently used language
- Compiled into EVM bytecode before execution

[`top`](#Virtual-Currency)

----

## Ethereum: The EVM

**The Ethereum Virtual Machine (EVM)**

The EVM’s physical instantiation can’t be described in the same way that one might point to a cloud or an ocean wave, but it does exist as one single entity maintained by thousands of connected computers running an Ethereum client.

The Ethereum protocol itself exists solely for the purpose of keeping the continuous, uninterrupted, and immutable operation of this special state machine; It's the environment in which all Ethereum accounts and smart contracts live. At any given block in the chain, Ethereum has one and only one 'canonical' state, and the EVM is what defines the rules for computing a new valid state from block to block.

Source: https://ethereum.org/en/developers/docs/evm/

[`top`](#Virtual-Currency)

----

## Ethereum: Distributed Apps

Distributed Apps are just smart contracts taken to the next level: they contain application code executed by smart contracts. 

The goal with distributed apps is to decentralized all aspects of an application: code execution, payments, storage, messaging, etc.

Not all DApps are completely descentralized: some rely on some centralization. 

[`top`](#Virtual-Currency)

----

## Ethereum: DeFi

The term DeFi was selected because it sounds like "defy."

DeFi allows for more than just payments. DeFi apps are smart contracts on Ethereum.
- Allows for lending and borroging funds (makerDao, Compound, AAVE)
- Stablecoins (DAI, USDC, USDT)
- Decentralized Exchanges (DEX)

Decentralized finance (DeFi) is based on secure distributed ledgers (blockchains). The DeFi system is designed to remove the control banks and institutions have on money, financial products, and financial services.

Some of the key attractions of DeFi for many consumers are:
1. It eliminates the fees that banks and other financial companies charge for using their services.
2. You hold your money in a secure digital wallet instead of keeping it in a bank.
3. Anyone with an internet connection can use it without needing approval.
4. You can transfer funds in seconds and minutes.

The components of DeFi are stablecoins, software, and hardware that enables the development of applications.

Source: https://www.investopedia.com/decentralized-finance-defi-5113835

[`top`](#Virtual-Currency)

----

## Ethereum: DEX

**DEX = Decentralized EXchanges**

Why decentralized exchanges?
- Permissionless (no KYC or AML regulation)
- censorship resistant
- access to tokens not offered on central exchange
- lower fees (cheaper to use; no overhead for buildings, lawyers, etc.)
- instant swap
- blockchain based (open)

Examples:
- [1inch.exchange](https://app.1inch.io/#/1/swap/ETH/DAI)
- [Uniswap](https://uniswap.org/)
- [Sushiswap](https://sushi.com/)

[`top`](#Virtual-Currency)

----

## Ethereum: Yield Farming

A DEX need funds to allow trades...
- Liquidity providers are rewarded for providing that liquidity (staking or locking crypto)
- Trading users pay a fee to swap token.
- Fees are paid to the Liquidity Provider (the Farmer)

Each pool on a DEX has to have to both tokens (Eth/USDC)
- Liquidity Providers (LPs) must contribute both assets to participate.
- They are rewarded in a third token, from the pool as a reward (called the "LP token")

Differences between farming and staking:
- Farming requires two types of Crypto minimum (Eth/USDC for example)
- With Faring you may receive a different amount of crypto back.

[`top`](#Virtual-Currency)

----

## Ethereum: Mining

Ethereum's mining algorithm/protocol is the same as bitcoin: Proof of Work (a cryptographic puzzle to solve).
- They are, however, looking to move to Proof of State (soon...).

Mining is the process of verifying transactions.
- Then a verified block is added to the blockchain
- And the miner who verified transaction AND solved the crytpo problem to verify the block, gets paid.

New blocks are added to the Ethereum Network about every 12 seconds.

Miners are rewarded Ether for solving the PoW problem
- Two newly minted Ether + all transaction fees (the "gas").

Blocks are chained together by their hashes; a block's parent hash is the previous block's hash.

[`top`](#Virtual-Currency)

----

## NFTs: Non-Fungible Tokens

### Definition & Description

**Fungibility** refers to the ability of a good or asset to be interchanged.
- It implies equal value between each of the items (a dollar is a dollar, wherever)
- Fungible: bitcoin, monero, ethereum, dogecoin, gold.
- Non-Fungible: digital art, a tweet, etc.

**NFTs are digital collectibles.**
- They are found on the blockchain as proof of ownership or authenticity

NFTs have NO fungibility, meaning each token is limited in production (should be only one; digitally unique).

This provides a way to track the sale of unique items such as: artwork, music, collectibles, land, real estate, marketing.

**ERC721** stands for "Ethereum Request for Comments 721": It is the standard that implements the application programming interface for tokens within smart contracts.
- Each token holds unique value (no two are the same)
- Example: CryptoKitties (one of the first NFTs)

**Gas & Fees:** Fees for buying, creating, and/or cancelling an auction on the Ethereum network. Determinted by:
1. Gas price or Gwei
2. Gas limit: sets the amount of gas use to process (max limit of what you want to spend)

**Popular NFTs:**
- [Beeple's "First 5000 days"](https://en.wikipedia.org/wiki/Everydays:_the_First_5000_Days): Sold for $69.3 million
- [Jack Dorsey's first tweet](https://www.forbes.com/sites/jeffkauflin/2022/04/14/why-jack-dorseys-first-tweet-nft-plummeted-99-in-value-in-a-year/?sh=43caf9b665cb): Sold for $2.9 million, originally.
- Etc.

**WHY:** Why are NFTs a thing?
- Because people like collecting and owning rare, unique things. It makes them feel special.
- It's also an excellent way to launder money from nefarious activities...

### Money Laundering

"Anti-Money Laundering" / "Know Your Customer": AML/KYC regulations... not applicable in a decentralized blockchain.

BSA: aimed at preventing criminals from hiding and laundering their money.
- covers cash and later they added art (hard to track art; good for money laundering)
- requires SARs for cash transactions of $10,000 or more

NFTs are great for money laundering because...
1. Bad guy creates a bunch of NFTs (stupid gifs, jpegs, etc.)
2. Bad guy "buys" his own NFTs with a different online identity.
3. Bad guy has "made money legally" by creating and selling NFTs (they are totally worthless in and of themselves and relatively free to make), and only lost the minimal fee of the sale.

**How easy could it be...?**
- Create a wallet with some Ethereum.
- Connect the wallet to Rarible.  https://rarible.com/
- Publish some NFTs.
- Have a relationship/pact formed with the account holder to overbid on NFTs.
- Pay for NFT with Ethereum, cash out, and provide a fee to the creator.
- Thereby "washing" your money

[`top`](#Virtual-Currency)

### Rarible

[Rarible](https://rarible.com/) is an NFT marketplace

On the Ethernet Network, an NFT from Rarible shows up as a "RARI Token 2" (or RARI Token 1)

Can chat with NFT owner: https://chat.blockscan.com/start  (on the Ethereum Network)

[`top`](#Virtual-Currency)

----

## Stable Coins

Standard cryptocurrency is similar to fiat currency in that value exists because you and I agree on value (of the "token" we are exchanging).

Stablecoins are similar to the gold standard: they are tied to and backed by a particular commodity. 
- Can be pegged to: fiat, commodity (gold, oil), crypto, etc.
- Backing: there must be enough collateral in reserve for each token of the stablecoin.

First Stablecoin (Tether) released in 2014
- It was pegged to the US Dollar
- [Whitepaper](https://assets.ctfassets.net/c5bd0wqjc7v0/79db1PxjBTv1JbL574fFvA/61e9950c436df5556c878d94bfcee855/CBI-StablecoinWhitepaper-July2022.pdf)

Stablecoins require audits (where standard crypto does not).
- Audits come out quarterly.

Stablecoins are centralized (where standard crypto is decentralized).

**Stablecoins cannot be mined.**

Stablecoins do not have their own blockchain. These tokens will reside on Ethereum Network, or a lesser blockchain. Examples:
- Tether
- Dai
- USD Coin
- True USD
- Paxos Standard
- Gemini Dollar
- PAX Gold

**Most common form of collateralization: Fiat backing**
- backed by real-world assets, off the chain, IRL
- Banks, treasury, stocks/bonds

Trust lies in the custodian of the backing asset.

Fees are required for maintaining the backing reserve, legal compliance, and audits.

Therefore they must have the fiat or commodity on hand.

[`top`](#Virtual-Currency)

### Purpose

Stablecoins are digital assets that aim to **manage volatility**.
- Value is linked to stable assets. This reduces the need to exchange crypto to fiat.
- Exchanges cost.
- Future may include retailers accepting a stablecoin. 
- Most frequent concern with digital assets is volatility.
- Stablecoins could allow global acceptance of crypto.

[`top`](#Virtual-Currency)

### Examples

Different Stable Coins:
- Terra Luna
- Tether
- Others: https://coinmarketcap.com/view/stablecoin/

[`top`](#Virtual-Currency)

----

## Privacy Coins: Monero

**Prac App:** (do this) Download and install some wallets for all these crypto currencies. Just play around with them. Don't have to buy any crypto, just familiarize yourself with the environment. 

**Whitepaper:** by Nicholas van Saberhagen, 10/17/2013 [pdf](https://cryptonote.org/whitepaper.pdf)

Monero is a decentralized blockchain-based privacy-currency platform.
- Monero is based on the CryptoNote protocol.
- CryptoNight is the proof-of-work hash algorithm

Unlike other crypto, Monero is designed to be secure, private, and anonymous.
- It focuses on decentralization, fungibility, and privacy.

Monero's Cryptocurrency Token: XMR or m
- Moneroj = plural of Monero
- Can be divided into smaller units
  - smallest unit is the piconero
  - 1,000,000,000,000 piconero = 1 Monero

**Wallets:**
1. Desktop: Monero, My Monero
2. Mobile: Cake Wallet
3. Hardware: Ledger Nano, Trezor, Kastelo (beta)
4. Paper: printed QR codes and keys (private and public)

Every Monero public address begins with 43 and has 95 characters in length.
- Funds are NOT associated with the Public address.
- Address won't tell you how "rich" a person is
- This is UNLIKE bitcoin in both scenarios

Three prongs are built into Monero's privacy process...

[`top`](#Virtual-Currency)

### Stealth Address (recipient)

This is the "Secret View Key". It is part of the inherent privacy of Monero.
- It protects the recipient; obfuscates the recipient's true address by generating a new one for each transaction. 
- Use the recipient's public address to create the stealth address (therefore it protects the recipient).
- Requires the sender to create random one-time address for every transaction on behalf of the recipient.
- Allows recipient to publish just one address, yet have all incoming payments go to unique addresses on the blockchain, which cannot be linked back to either the recipient's published address or any other transaction addresses.
- By using stealth addresses, only the sender and receive can determine where a payment was sent.

**Transactions:**
- Associated with one-time addresses that are not linked to public addresses.
- When funds are sent to someone's public address, the funds are actually sent to a randomly created brand new one-time destination address called "Stealth Address"

Public addresses NEVER appear on the blockchain (it's the stealth key).

When you launch your wallet, Monero scans the blockchain and checks for transactions where you are the recipient (your "secret view key").

[`top`](#Virtual-Currency)

### Ring Signature (sender)

The ring **signature** protects the sender, the **signer**.
- This works like a "transaction mixer" (random users moving Monero around) to obfuscate the true sender.
- The "ring" is a "ring" (group) of Monero users (randomly picked). 
- Ring size is fixed at 11 (used to be 4-25, variable). One true sender and 10 decoys.
- It makes use of account keys and a number of public keys (also known as outputs) pulled from the blockchain using a triangular distribution method.
- Over the course of time, past outputs could be used multiple times to form possible signer participants.
- In a "ring" of possible signers, all ring members are equal and valid... obfuscates the trail... of who sent (signed) the transaction. Sender's signature is obfuscated by the other random "decoys."

[`top`](#Virtual-Currency)

### RingCT (transaction)

The RingCT: Ring Confidential Transactions
- Hides the source and the amounts of funds sent; cannot be seen on the blockchain.
- They do this by applying mathematical function to all funds such that the public observers can see that the transactions are legitimate, but only the sender and receiver can know the amount.

[`top`](#Virtual-Currency)

### Mining

CryptoNight Proof of Work consensus algorithm
- new block about every 2 minutes
- CPU based mining (vs. GPU based like bitcoin)
- like bitcoin, contains a degree of difficulty to maintain the two-minute cycle
- Block numbers are referred to as the "height"

[`top`](#Virtual-Currency)

----

## Tracing Techniques

### Documentation

Document! Document! Document what you do!
- Document the investigative process.
  - when information was accessed / collected
  - How the information was accessed / collected
  - What content was accessed / collected
- Critical in all investigations
- Following cryptocurrency transactions, it is even more critical to document extensively.
  - Keys can look similar
  - Easy to get click-happy
  - Slow and steady wins the race; be clean and efficient

[`top`](#Virtual-Currency)

### Screenshots

Screenies are your friend...
- Features: entire screen, specific window, specific region, delayed trigger
- Tools:
  - Windoze: Snipping tool
  - Mac: Apple Screenshot
- What to snip: URL bars, time-date stamps, what shows where you were or when...
  - anything you can get to document your investigation
  - snip as much info as you can (time/date, url, et al -- any info critical/important)
  - be consistent in your methodology

[`top`](#Virtual-Currency)

### Screen Recorders

Screen recorders can give a better picture of the flow of information. 
- Features: entire screen, specific window, specific region, audio recording
- Tools:
  - XBox Game Bar  (Windows Key + G; ESC to close it out)
  - Apple Quicktime Player
  - Apple Screenshot
  - TechSmith SnagIt / Camtasia
- Be careful: it will likely record audio, and you do not want that in your file unless it's supposed to be there.

[`top`](#Virtual-Currency)

### Hunchly 

Hunchly is a chrome extension, paid ($$) utility
- Automatically captures:
  - Full web pages as they are visited
  - Searches performed
- Automatically scan for keywords
- Can capture images(preserves metadata)
- All data is stored locally (can be imported and exported)

[`top`](#Virtual-Currency)

### Step 1: Identify Keys

**Where** might you find keys... wallet addresses... etc.?
- Printed paper wallets
- Handwritten notes
- Email/forum signatures
- Business cards
- Social media
- Seized computers / mobile devices
- victim reports (look for Transaction ID or address where the funds were sent to)
- during questioning

**Bitcoin Addresses:**
- Also known as a "public key"
- Alphanumeric value used as the destination of a bitcoin transaction
- Will start with a 1, 3, or bc1.  Types:
    P2PKH  (alias: Legacy) - Starts with 1   [used only one private/public key pair; single]
    P2SH   (alias: Segwit) - Starts with 3   [Segregated Witnesses; Multi-Sig Address]
    P2WPKH (alias: Bech32) - Starts with bc1
    P2WPH  (alias: Bech32) - Starts with bc1
- Can also be represented by a QR Code (make sure you get this on your search warrant)

**Private Keys:** This is the "secret value."
- Needed to sign transactions and spend bitcoin.
- 256-bit number (can be displayed in a variety of ways)
- Mathematically related to a public key
  1. Wallet Import Format (WIF) - Uncompressed Pubkey: starts with 5
  2. WIF - Compressed Pubkey: starts with K or L

**BEST: Mnemonic Seed Phrase:**
- This will get you into an ENTIRE WALLET.
- List of words created by a deterministic wallet
- Used to backup your entire wallet (that can have multiple private/public key pairs)

**Bitcoin Transaction ID:**
- A 32-byte hexadecimal value (256 bit hash of the transaction)
- If you can obtain this, you have a direct link to the transaction in question (and from there you can trace to sender, receiver, etc.)

[`top`](#Virtual-Currency)

### Step 2: Trace Transactions

Follow this routine, in order (then run through it again for additional addresses, etc.)
1. You usually start with an address (public address, transaction ID, etc.).
2. Interrogate the address(es) - find out as much general info as you can
   - Related addresses
   - Usage statistics
   - Number of transactions
   - Get as much info about this address as you can
   - THEN: You might want to monitor this address/wallet. (more below)
3. Interrogate transactions (identify change and payment, so you don't "chase change")
   - Take your time. Take good notes. Don't get click-happy. Document. Understand the movement.
   - Try to visualize the transactions (might be necessary for court: flowchart, org chart, etc)
     - There are visualization sites that can assist with this.
     - But save this until the end of the investigation, as a summary to "paint the picture"
4. Identify exchanges/services
   - Somewhere you might be able to serve a legal process.

**Don't forget to use traditional search platforms!**
- OSInt crap, searching on the address, transaction ID, etc.
  1. Google is your friend
  2. Pastebin (dump in your address and see if it has been used before)
  3. RiskIQ
  4. Threat Connect
  5. Social Media
  6. Cryptocurrency forums (Bitcoin Talk, etc.)
  7. BitCoin WhosWho (https://www.bitcoinwhoswho.com/)

**Watch a Wallet:**
- You may not have a transaction; you may be waiting on one to happen so you can ID the perp.
- Use a service like [Blockonomics[(https://www.blockonomics.co/) to watch the wallet and get notifications if there is movement.

**Know Your Tools:**
- [BlockChain.com/Explorer](https://www.blockchain.com/explorer): very good explorer for crypto
- [BlockChair](https://blockchair.com/): another good explorer
- [BlockCypher](https://www.blockcypher.com/) and [BlockCypher Live](https://live.blockcypher.com/): another explorer
- [CrystalBlockChain](https://explorer.crystalblockchain.com/): this explorer **might show the owner of the account you're investigating.**
- [WalletExplorer.com](https://www.walletexplorer.com/)
  - ChainAlysis. Originally built as a honeypot.
  - It ties wallet addresses together (correlation routines)
- [Etherscan](https://etherscan.io/): for Ethereum
- [BSCScan](https://bscscan.com/): 
- Others: [Chainz CryptoID](https://chainz.cryptoid.info/), [CoinGecko](https://www.coingecko.com/), [CoinMarketCap](https://coinmarketcap.com/)

[`top`](#Virtual-Currency)

----

## Links & Resources

### Launching Pad
https://coinmarketcap.com/
- look up crypto currencies and this site will give you resources to trace, learn, etc. for that currency
- this is your first stop to get moving on your investigation
- it also has a "news" section for each currency
https://start.me/p/m6r1AM/virtual-currency-course-links

[`top`](#Virtual-Currency)

### BitCoin Terms
https://bitcoin.org/en/vocabulary

[`top`](#Virtual-Currency)

### Explorers, BitCoin
https://www.blockchain.com/explorer
https://blockchair.com/
https://www.blockcypher.com/
https://live.blockcypher.com/
https://explorer.crystalblockchain.com/ (might show the owner of the account)

[`top`](#Virtual-Currency)

### Explorers, Ethereum
https://etherscan.io/

[`top`](#Virtual-Currency)

### Explorers, Other
BSCScan: https://bscscan.com/
Wallet Explorer: https://www.walletexplorer.com/

[`top`](#Virtual-Currency)

### Exchanges
- Coinbase: https://www.coinbase.com/
- Coinbase Pro: https://pro.coinbase.com/
- Coinbase Pro Example: https://pro.coinbase.com/trade/BTC-USD
- Peer-to-Peer Exchange: https://localbitcoins.com/

[`top`](#Virtual-Currency)

### BitCoin ATMs 
https://coinatmradar.com/
- This site will have contact info for the providers of the ATMs (to contact them during investigations)
- The only people who use ATMs are criminals and victims: the surcharge is astronomical and the fees are robbery.

[`top`](#Virtual-Currency)

### NFTs
Rarible: https://rarible.com/
Chat with NFT owner: https://chat.blockscan.com/start  (on the Ethereum Network)

[`top`](#Virtual-Currency)

### Trackers
https://www.cointracker.io/
Blockonomics: https://www.blockonomics.co/

[`top`](#Virtual-Currency)

### Crypto Abuse
Public "Reporting" of Abuse: https://www.bitcoinabuse.com/

[`top`](#Virtual-Currency)

### Visualization

Visualization with Crystal Blockchain Explorer:
- Do your investigation first. Trace the funds. THEN use this to visualize it.
https://explorer.crystalblockchain.com/visualization/new/1NDyJtNTjmwk5xPNhjgAMu4HDHigtobu1s

[`top`](#Virtual-Currency)
