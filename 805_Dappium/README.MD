# Dappium: No-Code Web3 Platform

## Description
Dappium is a no-code web3 builder. If you are a web2 developer (e.g. a game studio) and want to tap into web3 but don’t want to build and maintain a blockchain development team, then you use Dappium. It creates all the smart contracts you would need automatically for you. It also gives you a web2 SDK to access your smart contracts from within your app code. You just select from the menu of web3 use cases, fill in web forms, click buttons to describe the system what you want. Dappium takes care of the rest, isolating all the technical complexities of web3 from the user.
If there is any functionality missing in your automatically created smart contracts, i.e. any parameter missing in the relevant forms you fill in, you fill in the tailor section of the form, and we develop it for you free of charge and add it to the code generator stack. This unique loop
has helped and will continue to help the Dappium no-code tool progress in an evolutionary manner;
provides the user the experience of having a tier-1 web3 team in house;
brings open-source reusability to no-code efficiency, and
enables a fine mix of flexibility and constraints (for security and optimization).
The smart contracts can cover all your needs such as crypto currency, entire tokenomics, staking, raffles, DAO contracts, NFT collection minting & management, marketplaces, wallets, loot boxes, more flexible and niche needs, etc. Dappium encompasses contract development, deployment (testnet and mainnet), management, utility, API, RPC infrastructure, etc. The platform isolates all the technical complexities of advanced Web3 systems from the Web2 developer (e.g. how do i get interoperability, what is bridging, multi-chain, custodial wallet, fiat friendly option, hybrid/single sign-on authentication, decentralized storage, etc.). Dappium partners with ecosystem players to achieve 360 service through a single platform.
Furthermore, web2 developers who are interested in web3 are scared of security issues and vulnerabilities. Hacking stories per capita is much higher in web3. One of the reasons Dappium team embarked on the mission is to force and spread best practices for optimization & security on web3 implementations. We do not want smart contract developers to introduce vulnerabilities on and around smart contract level. All the co-founders are prominent computer scientists and electronics engineers with a great deal of start-up experience involving high tech security software development. Dr. Guven Fidan and his team has developed many security frameworks and software middleware for banks, etc. If you Google “super-rational attack” you will see one of the many posts written by Ersin Taskin (a co-founder) on the Cryptography maillist on web3 security. Ersin Taskin is co-founder and CTO of Kod-A the developer of GreenDocs. Salih Kanli is the co-founder of CBKSoft developing enVision™ BPM and DMS, which is used by government institutions, banks, utilities, universities, etc. All their web2 enterprises has evolved around a high level of security. Detailed credentials can be provided.

## Status


Grant Accepted / **In progress** / Completed

## Links

- DEVxDAO [Grant link](https://portal.devxdao.com/public-proposals/805)

- casperecosystem.io[Grant link]()

- public project chat

- [Twitter](https://twitter.com/dappium)

## Milestones

### M1

Deadline 3/31/2023

Integrating Casper Network to Dappium.io, deploying Dappium.io development environment on Casper.Network Testnet for the entire team


#### Description

Study Casper.Network technical fundamentals, architecture, smart contract languages, etc.
Install and configure the Dappium Casper development environment (dependencies, etc.) for the Dappium developer team.
Develop / convert the automatic CEP-18 (ERC20) Token Creation module.
Alpha Test.
Beta test with a Dappium user.

#### Acceptance criteria

Criteria 1: Users are able to design, develop and deploy an CEP-18 (ERC-20) token no-code using Dappium UI/UX.

How to check: 
Go to Dappium.io as a registered user.
Click Create Token. 
Fill in the form to describe your token attributes. 
Select CEP-18 as token type.
Select Casper Testnet as the network.
Click Save. 
Get the address of the relevant smart contract. 
Check the smart contract deployment on https://cspr.live/. 
Interact with the smart contract with your wallet. (I.e. transfer tokens).
Audit the smart contract.


#### Reports

### M2


Deadline 5/15/2023

No-code Tokenomics Module on Casper Network


#### Description

After getting the core Dappium functionality on Casper Network and getting our no-code crypto currency generator module, we then implement our no-code tokenomics module. In this module the user can design, test and deploy the entire tokenomics smart contracts for a token on the Casper Network, securely & no-code.


#### Acceptance criteria

Criteria 1: Users are able to design, develop and deploy entire tokenomics for a token no-code using Dappium UI/UX.

How to check: 
Go to Dappium.io as a registered user.
Select a token, click Tokenomics and then Create Tokenomics. 
Enter tokenomics round information (Name, various vesting conditions, cliff, TGE, supply, whitelist). 
Click Save. 
Get the address of the relevant smart contract. 
Check the smart contract deployment on https://cspr.live/. 
Interact with the smart contract with your wallet (Casper Wallet, Torus). (I.e. transfer tokens).
Create and test the entire tokenomics smart contracts with all tokenomics round information combinations like whitelisted or not, various vesting conditions, cliff, TGE, supply, etc.
Inspect the smart contracts.

#### Reports

### M3

Deadline 5/15/2023

No-code NFT Module on Casper Network


#### Description

We develop / convert the no-code NFT (CEP-78) module on Casper Network.
The users can do the following on Casper, no-code using Dappium NFT Module (i.e. The Casper NFT Module will create and deploy the relevant smart contracts automatically and provide web2 SDK’s to access the smart contracts.):

Create and mint NFT Collections (CEP-78) for their projects/games. 
Create lootboxes and manage them by importing NFT items from various collecitons. (Lootbox smart contracts are used in Web3 games so that a lootbox can store NFT items from various collections).
Create mergeable NFT’s.
Create timed NFT’s.
Assign NFT collections to games or apps.
Create in app/game NFT Marketplace: The NFT’s created are tradable in 3rd party marketplaces and in app/game marketplace. Therefore, developing an in-app marketplace is crucial. Dappium NFT module will include functionality to do it no-code.

The system will support CEP-78 standard.

#### Acceptance criteria

Criteria 1: Users are able to design and mint NFT Collections of various types in CEP-78 standard,  no-code using Dappium UI/UX.

How to check: 

The user tests the following NFT Module functionality on Dappium.io app.

Design and mint NFT Collections of various types. 
Check the relevant smart contracts deployed on Casper Network via https://cspr.live/.
Test the NFT Collection smart contracts by minting, trading NFT items.
Create Mergeable NFTs.
Check the relevant smart contracts deployed on Casper Network via https://cspr.live/.
Test the NFT Collection smart contracts by minting, trading NFT items.
Create Lootboxes
Check the relevant smart contracts deployed on Casper Network via https://cspr.live/.
Test the NFT lootbox smart contracts by using lootboxes in games. The developer can use the Unity or Unreal SDK to interact with a game code.
Create an in-app NFT Marketplace for the above NFT collections. 
Check the relevant smart contracts deployed on Casper Network via https://cspr.live/.
Test the NFT Marketplace smart contracts by trading NFT items on it.

#### Reports

### M4

Deadline 6/30/2023

Staking & Raffles Modules


#### Description

Two modules will be delivered on Casper Network in this milestone:
Staking Module: The user can use this module to design, create and deploy staking smart contracts for its fungible and non-fungible tokens. The APR are normally dynamic according to decentralized staking algorithms, however, constant APR’s are possible using the Dappium Staking Module. This helps users of the system provide constant revenue assurance for their client. 
Staking contracts can have various rules and information like:
Fixed or dynamic APR, Fixed APR %, Token Type, Max Cap, Minimum nd Maximum Stake per Wallet, Lock Period, Deposit Start Time, Deposit End Time.

Raffles Module: Raffles are used extensively in web3 applications. The user can design and deploy raffles smart contracts no-code using the Raffle Module. The user can enter a raffle name, select an NFT Collection, enter price, Raffle Start Time, and End Time for the relevant smart contract.

Web front-end is available to use the Staking and Raffle smart contracts. Users can also access their smart contracts via the SDK’s they can download from Dappium.io.



#### Acceptance criteria

Criteria 1: Staking Module.
Users are able to design, develop and deploy web3 staking for a token, no-code using Dappium UI/UX.

How to check: 
The user tests the following Staking  functionality on Dappium.io app.
Select a token on Casper Network and click Staking.
Fill in the Staking contract design webform. (Fixed or dynamic APR, Fixed APR %, Token Type, Max Cap, Minimum and Maximum Stake per Wallet, Lock Period, Deposit Start Time, Deposit End Time.)
Click Save.
Check the relevant smart contract deployed on Casper Network via https://cspr.live/.
Test the staking smart contract by interacting with it on the automatically generated web front-end on Dappium.io or using any SDK provided by Dappium.

Criteria 2: Raffle Module
Users are able to design, develop and deploy web3 raffles for a token, no-code using Dappium UI/UX.

How to check: 
The user tests the following Raffle functionality on Dappium.io app.
Go to Raffles tab on Dappium.io.
Fill in the Raffles contract design webform. (Name, Collection Address, NFT Collection Address, Price, Raffle Start Time, and End Time)
Click Save.
Check the relevant smart contract deployed on Casper Network via https://cspr.live/.
Test the raffles smart contract by interacting with it on the automatically generated web front-end on Dappium.io or using any SDK provided by Dappium.


#### Reports

### M5

Deadline 8/31/2023

Custodial Wallet


#### Description

Dappium.io plans to provide wallet options to the users. Casper wallet, Dappium custodial wallet, etc. Creating a secure custodial wallet for a web3 game requires a combination of technical knowledge and security expertise. It's important to carefully design, implement, and test the wallet to ensure it can be used safely and securely by players. We have  experience in booth security and the technical knowledge base. For each player and the game studio users we will generate custodial wallets where the private keys will be stored securely. We will use Key Management Services (KMS) such as Amazon KMS for this purpose. 

To secure wallet private keys in Amazon KMS, we will in general follow the following steps:
 
We will create a platform master key in Amazon KMS. This is the key that will be used to encrypt and decrypt your private keys.
We will use the encrypt function in the Amazon KMS API to encrypt the wallet private keys using the platform master key  just created. This will return a ciphertext that we can store securely.
We will then store the ciphertext in a password-protected storage service.
When we need to use private keys, we will use the decrypt function in the Amazon KMS API to decrypt the ciphertext and retrieve the  private keys only on microservice internal functions.
Overall, using Amazon KMS to encrypt and store wallet private keys can help protect them from unauthorized access. It's important to note that this method will not be adequate for full security but we add more Symmetric and Asymmetric key usages for extra securing the private keys that we could not give in detail.


#### Acceptance criteria

Open a user account. 
Check the balances at the public address of the custodial wallet corresponding to the user. 
Send money to the user account using the Custodial API from another Dappium custodial wallet address and check the balance.
Send money to the user account using the Custodial API from another non-custodial wallet address and check the balance.
Withdraw token from the custodial account to any wallet address. Check the balances. 
Check the transaction details in all of the above tests.

#### Reports


### M6

Deadline 7/31/2023

First Dappium Game Launch on Casper


#### Description

In this milestone we plan to onboard the second Dappium game to deploy its web3 component on Casper.

#### Acceptance criteria

Check to see the smart contracts of the relevant game on Casper.network.


#### Reports


### M7

Deadline 8/31/2023

Second Dappium Game Launch on Casper


#### Description

In this milestone we plan to onboard the second Dappium game to deploy its web3 component on Casper.


#### Acceptance criteria

Check to see the smart contracts of the relevant game on Casper.network.

#### Reports



