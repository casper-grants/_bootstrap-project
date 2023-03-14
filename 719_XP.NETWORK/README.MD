# Fondant: Ganache-like testing environment for Casper blockchain.


## Description
Without bridges, blockchains are like islands. Assets cannot move freely between them and access each other's markets increasing liquidity. Bridges solve this problem.
While many bridges provide for fungible token transfers, there's a giant gap in NFT transferring between chain protocols and marketplaces which our solution fills.
We have already received 17 grants from interested blockchains and have integrated 21 chains. We believe the Casper community deserves to be interwoven into the world NFT ecosystem as soon as possible.

XP.NETWORK Multi-Chain NFT Bridge will open 21 already integrated chains' markets to the Community on Casper and make NFTs & SFTs natively minted on Casper available to a huge user base of the linked chains. As we will keep integrating more chains, Casper will be automatically linked with the new ledgers out of the box.

## License

MIT License

## Status

**Grant Accepted** / In progress / Completed

## Links

- DEVxDAO [Grant link](https://portal.devxdao.com/app/proposal/719)

- casperecosystem.io[Grant link]()

- public project chat

- [Twitter]()

## Milestones

### M1
deadline 18.12.2022

#### Description

Smart Contract Development

0. Research about Casper standards and other factors & protocols that distinguish it from other chains
1. Learn to programmatically deploy contracts
2. Freeze/Unfreeze Native NFTs
3. Mint/Burn wrapped NFTs
4. Trust the multi-signature of the bridge oracle validators
5. Whitelist NFT smart contracts
6. Pause/Unpause for maintenance or if compromised
7. Collect payment for the transaction from the asset sender
8. Reimburse the Validators their expenses
9. Inline doc strings

#### Acceptance criteria

When tests accompanying the smart contracts can:
1. Deploy smart contracts
2. Mint & Burn NFTs
3. Freeze/unfreeze NFTs
4. Sign transactions with the FROST generated multi-signature and smart contract can verify validity of such signature
5. Whitelist NFT smart contracts
6. Pause/Unpause for maintenance or if compromised
7. Collect payment for the transaction from the asset sender
8. Send tokens to an authorised account
9. Crucial parts of the smart contract source code accompanied with doc strings.


#### Reports

[Milestone 1](m1.md)

### M2
deadline 01.01.2023

#### Description

Testing & Documentation

1. Deployment of the smart contracts on the chain Testnet.
2. Adding the deployed contracts to the JS library
3. Developing the logic in the bridge validators
4. Adding the chain Testnet to the nft-indexer
5. A testing tutorial in markdown accompanied with typescript examples of usage

#### Acceptance criteria

1. Chain Explorer links to the deployed smart contracts
2. Links to the lines of code in the public xpjs library
3. Successful transaction links on the Testnets
4. Being able to view JSONs of a user's Testnet NFTs via the nft-indexer
5. A tutorial of using the JS Library in markdown format accompanied with the code snippets in TS

#### Reports

### M3
deadline 15.01.2023

#### Description

UI & Mainnet integration

1. Adding the chain to the bridge UI
2. Adding the chain to the bridge widget
3. Integrating with a browser Extension / mobile wallet
4. Deploying contracts on the chain Mainnet
5. Adding the Mainnet contracts to the JS library
6. Adding the Mainnet nft-indexing
7. Testing NFT transfers from the chain and to the chain

#### Acceptance criteria

1. The chain is available in the bridge UI as departure or destination
2. The chain is available in the bridge widget as departure or destination
3. The UI & the widget allow signing transactions via a browser extension &/or mobile wallet
4. Links to the chain Mainnet explorer with the deployed contracts
5. Being able to view JSONs of a user's Mainnet NFTs via the nft-indexer
6. Links to the chain Mainnet explorer with the successful bridging transaction




