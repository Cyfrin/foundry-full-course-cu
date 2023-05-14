*This repo is a work in progress*

# Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023

Welcome to the repository for the Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023

*Video coming soon...*

## Recommended Tools
- Recommended Testnet: Sepolia
- Recommended DevOps: [foundry-devops](https://github.com/ChainAccelOrg/foundry-devops)

# [Testnet Faucets](https://faucets.chain.link)
Main Faucet:<a href="https://faucets.chain.link" target="_blank"> https://faucets.chain.link</a>
Backup Faucet:<a href="https://sepoliafaucet.com/" target="_blank"> https://sepoliafaucet.com/</a>

> ⚠️ All code associated with this course is for demo purposes only. They have not been audited and should not be considered production ready. Please use at your own risk. 

# Resources For This Course

### Questions

- [ChatGPT](https://chat.openai.com/)
    - Just know that it will often get things wrong, but it's very fast!
- [Phind](https://www.phind.com/)
    - Like ChatGPT, but it searches the web
- [Other AI extensions](https://twitter.com/aisolopreneur/status/1654823630155464704?s=42&t=-pu_sCYtfrfPJU7OXfifrQ)
- Github Discussions 
    -   Ask questions and chat about the course here!
-   [Stack Exchange Ethereum](https://ethereum.stackexchange.com/)
    -   Great place for asking technical questions about Ethereum
-   [Peeranha](https://peeranha.io/)
    -   Decentralized Stack Exchange!


New: Each lesson gets an NFT, and a "where to learn more" section. Maybe on ZKSync? Have a section be "moving funds to an L2". 

TODO: Add gitpod

- [Blockchain Developer, Smart Contract, \& Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023](#blockchain-developer-smart-contract--solidity-course---powered-by-ai---beginner-to-expert-course--foundry-edition-2023)
  - [Recommended Tools](#recommended-tools)
- [Testnet Faucets](#testnet-faucets)
- [Resources For This Course](#resources-for-this-course)
    - [Questions](#questions)
- [Lesson 0: Welcome to the Course!](#lesson-0-welcome-to-the-course)
- [Lesson 1: Blockchain Basics](#lesson-1-blockchain-basics)
- [Lesson 2: Welcome to Remix - Remix Simple Storage](#lesson-2-welcome-to-remix---remix-simple-storage)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes)
- [Lesson 3: Remix Storage Factory](#lesson-3-remix-storage-factory)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes-1)
- [Lesson 4: Remix Fund Me](#lesson-4-remix-fund-me)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes-2)
- [Lesson 5: AI Prompting, Asking Questions, and Getting Help](#lesson-5-ai-prompting-asking-questions-and-getting-help)
- [Lesson 6: Foundry Simple Storage](#lesson-6-foundry-simple-storage)
  - [Installation \& Setup (MacOS \& Linux)](#installation--setup-macos--linux)
    - [Windows Setup](#windows-setup)
    - [Gitpod](#gitpod)
  - [Local Development Introduction](#local-development-introduction)
  - [Deploying to a testnet or a mainnet](#deploying-to-a-testnet-or-a-mainnet)
  - [TODO: Add FCC bash lessons](#todo-add-fcc-bash-lessons)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes-3)
- [Lesson 7: Foundry Fund Me](#lesson-7-foundry-fund-me)
  - [Introduction](#introduction)
  - [Setup](#setup)
  - [Mocking](#mocking)
  - [Networking](#networking)
  - [Programmatic Verification](#programmatic-verification)
  - [Interactions.s.sol](#interactionsssol)
  - [Testing](#testing)
  - [Debugging \& Coverage](#debugging--coverage)
  - [Style Guide](#style-guide)
  - [Gas III](#gas-iii)
  - [Storage](#storage)
  - [Pushing to GitHub](#pushing-to-github)
- [TODO: Fix the tweet for paradigm instead of hardhat](#todo-fix-the-tweet-for-paradigm-instead-of-hardhat)
  - [🐸🐦 Tweet Me (add your repo in)!](#-tweet-me-add-your-repo-in)
  - [Recap](#recap)
- [Lesson 8: Html/Js Fund Me (Quick Fullstack / Front End Tutorial)](#lesson-8-htmljs-fund-me-quick-fullstack--front-end-tutorial)
- [Lesson 9: Foundry Smart Contract Lottery](#lesson-9-foundry-smart-contract-lottery)
  - [Raffle.sol Setup](#rafflesol-setup)
  - [Introduction to Events](#introduction-to-events)
  - [Events in Raffle.sol](#events-in-rafflesol)
  - [Introduction to Chainlink VRF](#introduction-to-chainlink-vrf)
    - [Sub-Lesson: Chainlink VRF](#sub-lesson-chainlink-vrf)
  - [Implementing Chainlink VRF - Introduction](#implementing-chainlink-vrf---introduction)
  - [Implementing Chainlink VRF - The Request](#implementing-chainlink-vrf---the-request)
  - [Implementing Chainlink VRF - The FulFill](#implementing-chainlink-vrf---the-fulfill)
    - [Modulo](#modulo)
  - [CEI](#cei)
  - [Introduction to Chainlink Automation](#introduction-to-chainlink-automation)
  - [Implementing Chainlink Keepers - checkUpkeep](#implementing-chainlink-keepers---checkupkeep)
    - [Enums](#enums)
  - [Implementing Chainlink Keepers - checkUpkeep continued](#implementing-chainlink-keepers---checkupkeep-continued)
  - [Implementing Chainlink Keepers - performUpkeep](#implementing-chainlink-keepers---performupkeep)
  - [Code Cleanup](#code-cleanup)
  - [Deploying Raffle.sol](#deploying-rafflesol)
    - [Mock Chainlink VRF Coordinator](#mock-chainlink-vrf-coordinator)
    - [Continued](#continued)
  - [Raffle.sol Unit Tests](#rafflesol-unit-tests)
    - [Testing Events](#testing-events)
    - [Continued I](#continued-i)
  - [Cheatcodes - vm.warp](#cheatcodes---vmwarp)
    - [Continued II](#continued-ii)
  - [Callstatic](#callstatic)
    - [Continued III](#continued-iii)
    - [Continued IV](#continued-iv)
  - [Raffle.sol Staging Tests](#rafflesol-staging-tests)
  - [Testing on a Testnet](#testing-on-a-testnet)
    - [Recommended LINK amounts for Sepolia Staging Test:](#recommended-link-amounts-for-sepolia-staging-test)
  - [Conclusion](#conclusion)
- [Lesson 10: Foundry ERC20s](#lesson-10-foundry-erc20s)
  - [What is an ERC? What is an EIP?](#what-is-an-erc-what-is-an-eip)
  - [What is an ERC20?](#what-is-an-erc20)
  - [Manually Creating an ERC20 Token](#manually-creating-an-erc20-token)
  - [Creating an ERC20 Token with Openzeppelin](#creating-an-erc20-token-with-openzeppelin)
  - [Lesson 12 Recap](#lesson-12-recap)
- [Lesson 11: Foundry NFTs | MoodNFT](#lesson-11-foundry-nfts--moodnft)
  - [What is an NFT?](#what-is-an-nft)
  - [Code Overview](#code-overview)
  - [Foundry Setup](#foundry-setup)
  - [Basic NFT](#basic-nft)
    - [Write Tests](#write-tests)
  - [IPFS NFT](#ipfs-nft)
    - [Setting an NFT Mint Price](#setting-an-nft-mint-price)
    - [Deploy Script](#deploy-script)
    - [Uploading Token Images with Pinata](#uploading-token-images-with-pinata)
    - [Uploading Token URIs (metadata) with Pinata](#uploading-token-uris-metadata-with-pinata)
    - [Deploying](#deploying)
    - [Tests](#tests)
  - [SVG On-Chain NFT](#svg-on-chain-nft)
    - [What is an SVG?](#what-is-an-svg)
    - [Initial Code](#initial-code)
    - [Base64 Encoding](#base64-encoding)
  - [Advanced: EVM Opcodes, Encoding, and Calling](#advanced-evm-opcodes-encoding-and-calling)
    - [abi.encode \& abi.encodePacked](#abiencode--abiencodepacked)
    - [Introduction to Encoding Function Calls Directly](#introduction-to-encoding-function-calls-directly)
    - [Introduction to Encoding Function Calls Recap](#introduction-to-encoding-function-calls-recap)
    - [Encoding Function Calls Directly](#encoding-function-calls-directly)
    - [Creating an NFT TokenURI on-Chain](#creating-an-nft-tokenuri-on-chain)
    - [Deploy Script](#deploy-script-1)
  - [Deploying the NFTs to a Testnet](#deploying-the-nfts-to-a-testnet)
  - [Lesson 12 Recap](#lesson-12-recap-1)
- [Lesson 12: Foundry DeFi | Stablecoin (The PINNACLE PROJECT!! GET HERE!)](#lesson-12-foundry-defi--stablecoin-the-pinnacle-project-get-here)
  - [What is DeFi?](#what-is-defi)
  - [What is Aave?](#what-is-aave)
  - [Programmatic Borrowing \& Lending](#programmatic-borrowing--lending)
  - [WETH - Wrapped ETH](#weth---wrapped-eth)
  - [Depositing into Aave](#depositing-into-aave)
  - [Borrowing from Aave](#borrowing-from-aave)
  - [Repaying with Aave](#repaying-with-aave)
  - [Visualizing the Transactions](#visualizing-the-transactions)
  - [MEV](#mev)
  - [Smart Contract Audit](#smart-contract-audit)
  - [What is a stablecoin?](#what-is-a-stablecoin)
  - [Fuzzing](#fuzzing)
  - [Happy Bow-Tie Friday with Austin Griffith](#happy-bow-tie-friday-with-austin-griffith)
    - [More DeFi Learnings:](#more-defi-learnings)
- [Lesson 13: Foundry Upgrades](#lesson-13-foundry-upgrades)
  - [Upgradable Smart Contracts Overview](#upgradable-smart-contracts-overview)
  - [Types of Upgrades](#types-of-upgrades)
  - [Delegatecall](#delegatecall)
  - [Small Proxy Example](#small-proxy-example)
  - [Universal Upgradable Smart Contract](#universal-upgradable-smart-contract)
- [Lesson 14: Foundry DAO / Governance](#lesson-14-foundry-dao--governance)
  - [Introduction](#introduction-1)
  - [What is a DAO?](#what-is-a-dao)
  - [How to build a DAO](#how-to-build-a-dao)
- [Lesson 15: Smart Contract Security \& Auditing (For developers)](#lesson-15-smart-contract-security--auditing-for-developers)


# Lesson 0: Welcome to the Course!
- **Follow the repository:** While going through the course be 100% certain to follow along with the github repository. If you run into in an issue check the chronological-updates in the repo.
- **Be Active in the community:** Ask questions and engage with other developers going through the course in the discussions tab, be sure to go and say hello or gm! This space is different from the other industries, you don't have to be secretive; communicate, network and learn with others :)
- **Learn at your own pace:** It doesn't matter if it takes you a day, a week, a month or even a year. Progress >>> Perfection
- **Take Breaks:** You will exhaust your mind and recall less if you go all out and watch the entire course in one sitting. 
  **Suggested Strategy** every 25 minutes take a 5 min break, and every 2 hours take a longer 30 min break
- **Refer to Documentation:** Things are constantly being updated, so whenever Patrick opens up some documentation, open it your end and maybe even have the code sample next to you.
- **Use ChatGPT and/or the course chat**

# Lesson 1: Blockchain Basics
<same as the 32 hour course, but add in L2s>
<Add PoS>
<add optimistic vs zk L2>
<talk about side chain>

Wallets:
- [Metamask](https://metamask.io/)
- [Frame](https://frame.sh/)

# Lesson 2: Welcome to Remix - Remix Simple Storage

💻 Code: [https://github.com/ChainAccelOrg/remix-simple-storage-f23](https://github.com/ChainAccelOrg/remix-simple-storage-f23)

## TODO: Extra credit / Exersizes!

1. Deploy a contract to <L2>

# Lesson 3: Remix Storage Factory

💻 Code: [https://github.com/ChainAccelOrg/remix-storage-factory-f23](https://github.com/ChainAccelOrg/remix-storage-factory-f23)

## TODO: Extra credit / Exersizes!

1. Deploy a contract to <L2>

# Lesson 4: Remix Fund Me

💻 Code: [https://github.com/ChainAccelOrg/remix-fund-me-f23](https://github.com/ChainAccelOrg/remix-fund-me-f23)

## TODO: Extra credit / Exersizes!
Deploy to L2

# Lesson 5: AI Prompting, Asking Questions, and Getting Help

DO NOT SKIP THIS!!

# Lesson 6: Foundry Simple Storage

💻 Code: [https://github.com/ChainAccelOrg/foundry-simple-storage-f23](https://github.com/ChainAccelOrg/foundry-simple-storage-f23)

## Installation & Setup (MacOS & Linux)
-   [Visual Studio Code](https://code.visualstudio.com/)
    - [Crash Course](https://www.youtube.com/watch?v=WPqXP_kLzpo)
- [VSCode Keybindings](https://code.visualstudio.com/docs/getstarted/keybindings)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [What is a terminal?](https://code.visualstudio.com/docs/editor/integrated-terminal)

### Windows Setup
- [WSL](https://docs.microsoft.com/en-us/windows/wsl/install)
  - When working in WSL, use Linux commands instead of Windows commands
- [TroubleShooting](https://docs.microsoft.com/en-us/windows/wsl/troubleshooting)
- `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

> ⚠️ Please use Gitpod as an absolute last resort
### Gitpod
- [Gitpod](https://www.gitpod.io/)
  - **If using this, NEVER share a private key with real money on Gitpod**
  - Ideally you figure out the MacOS, Linux, or Windows install though

## Local Development Introduction
- `CMD + K` or `CTRL + K` clears the terminal
- `mkdir ethers-simple-storage-fcc`
- `code .` to open VSCode in a new VSCode window

Also do advanced stuff like:
cast
anvil
tests

- Format your solidity code with: 
```json
    "[solidity]": {
        "editor.defaultFormatter": "NomicFoundation.hardhat-solidity"
    },
    "[javascript]":{
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
```
[Ganache](https://trufflesuite.com/ganache/)
[ETH JSON RPC](https://ethereum.github.io/execution-apis/api-documentation/)

2 Ways to deploy:
1. `forge create`
2. `forge script`

```bash
cast --to-base 0x01 dec
```

## Deploying to a testnet or a mainnet
- [Alchemy](https://alchemy.com/?a=673c802981)
- [Someone fix this please](https://github.com/foundry-rs/foundry/issues/3818)
- [Example verified contract](https://sepolia.etherscan.io/address/0xe2e9f468eb7f063aa01670bb4bce4119fb6e4b65#code)
- [ThirdWeb Deploy](https://thirdweb.com/deploy)

## TODO: Add FCC bash lessons

## TODO: Extra credit / Exersizes!
Deploy to L2

# Lesson 7: Foundry Fund Me

💻 Code:[https://github.com/ChainAccelOrg/foundry-fund-me-f23](https://github.com/ChainAccelOrg/foundry-fund-me-f23)
## Introduction 

## Setup
- [Dependencies](https://book.getfoundry.sh/projects/dependencies)

## Mocking
- [Mocking](https://stackoverflow.com/questions/2665812/what-is-mocking)
- [Aave Github](https://github.com/aave/aave-v3-core)
- [Chainlink Github](https://github.com/smartcontractkit/chainlink)
- Multiple Versions of Solidity

## Networking
- [Chain ID List](https://chainlist.org/)

## Programmatic Verification
- [Etherscan API Key](https://docs.etherscan.io/getting-started/viewing-api-usage-statistics)

## Interactions.s.sol

## Testing
4 test tiers

1. [Unit](https://en.wikipedia.org/wiki/Unit_testing)
2. Integration
3. Forked
4. Staging

We cover 1 and 3. 

## Debugging & Coverage
- [Chisel](https://github.com/foundry-rs/foundry/tree/master/chisel)
- [Gas Reporter](https://book.getfoundry.sh/forge/gas-reports)
- Coverage
- [console.log](https://book.getfoundry.sh/reference/forge-std/console-log?highlight=console#console-logging)

## Style Guide
- [Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html)
  - [Chainlink Style Guide](https://github.com/smartcontractkit/chainlink/blob/develop/contracts/STYLE.md)
- [NatSpec](https://docs.soliditylang.org/en/latest/natspec-format.html)

## Gas III

## Storage
- [Storage Layout](https://docs.soliditylang.org/en/latest/internals/layout_in_storage.html)
- [Purpose of the memory keyword](https://stackoverflow.com/questions/33839154/in-ethereum-solidity-what-is-the-purpose-of-the-memory-keyword)

```
cast storage
```
- [Opcodes](https://ethereum.org/en/developers/docs/evm/opcodes/)
- [Opcodes by Gas](https://github.com/crytic/evm-opcodes)
- [Opcodes by Gas](https://evm.codes/)
- Append `s_` to storage variables
- Append `i_` to immutable variables
- Caps lock and underscore constant variables
- [Chainlink Solidity Style Guide](https://github.com/smartcontractkit/full-blockchain-solidity-course-js/issues/13)

## Pushing to GitHub
- [Git Docs](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [GitHub docs](https://docs.github.com/en)
- [Github Quickstart](https://docs.github.com/en/get-started/quickstart)
- [What is Git?](https://www.git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
- [The quickstart that we follow in the video](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#adding-a-local-repository-to-github-using-git)
- [Learn about git and GitHub](https://www.youtube.com/watch?v=RGOj5yH7evk)

# TODO: Fix the tweet for paradigm instead of hardhat

## 🐸🐦 [Tweet Me (add your repo in)!](https://twitter.com/intent/tweet?text=I%20just%20made%20my%20first%20Smart%20Contract%20repo%20using%20@solidity_lang,%20@HardhatHQ,%20@chainlink,%20@AlchemyPlatform,%20and%20more!%0a%0aThanks%20@PatrickAlphaC!!)

## Recap

# Lesson 8: Html/Js Fund Me (Quick Fullstack / Front End Tutorial)

💻 Code: [https://github.com/ChainAccelOrg/html-fund-me-f23](https://github.com/ChainAccelOrg/html-fund-me-f23)

# Lesson 9: Foundry Smart Contract Lottery

💻 Code: [https://github.com/ChainAccelOrg/foundry-smart-contract-lottery-f23](https://github.com/ChainAccelOrg/foundry-smart-contract-lottery-f23)

- debug TX

## Raffle.sol Setup
* Raffle.sol Setup
- Custom Errors in Solidity
## Introduction to Events
* Introduction to Events
- Events & Logging Video
- Events & Logging in Hardhat
## Events in Raffle.sol
* Events in Raffle.sol
## Introduction to Chainlink VRF
* Introduction to Chainlink VRF
- Special Guest <>
### Sub-Lesson: Chainlink VRF
> - Chainlink VRFv2 Docs
> - Chainlink VRFv2 Walkthrough
> - Chainlink Contracts
## Implementing Chainlink VRF - Introduction
* Implementing Chainlink VRF
## Implementing Chainlink VRF - The Request
## Implementing Chainlink VRF - The FulFill
### Modulo
- Modulo
## CEI
## Introduction to Chainlink Automation
- Chainlink Automation Docs
- Chainlink Automation Walkthrough
## Implementing Chainlink Keepers - checkUpkeep
### Enums
- Enum
## Implementing Chainlink Keepers - checkUpkeep continued
- block.timestamp
## Implementing Chainlink Keepers - performUpkeep
## Code Cleanup
## Deploying Raffle.sol
### Mock Chainlink VRF Coordinator
### Continued
- LINK Token
## Raffle.sol Unit Tests
### Testing Events
### Continued I
## Cheatcodes - vm.warp
### Continued II
## Callstatic
- Callstatic
### Continued III
### Continued IV
## Raffle.sol Staging Tests
## Testing on a Testnet
### Recommended LINK amounts for Sepolia Staging Test:
- Chainlink VRF: 2 LINK
- Chainlink Keepers: 8 LINK
## Conclusion

# Lesson 10: Foundry ERC20s

💻 Code: [https://github.com/ChainAccelOrg/foundry-erc20-f23](https://github.com/ChainAccelOrg/foundry-erc20-f23)

## What is an ERC? What is an EIP?
- What is an EIP?
- EIPs codebase
## What is an ERC20?
- Video (using brownie/python)
- EIP-20
- ERC-677
- EIP-777
## Manually Creating an ERC20 Token
- `.github`
## Creating an ERC20 Token with Openzeppelin
- Openzeppelin
- Openzeppelin Contracts
- Solmate (Openzeppelin alternative)
## Lesson 12 Recap


# Lesson 11: Foundry NFTs | MoodNFT

💻 Code: [https://github.com/ChainAccelOrg/foundry-nft-f23](https://github.com/ChainAccelOrg/foundry-nft-f23)


## What is an NFT? 
- Video
- Optional: All on Chain SVG NFT
- EIP-721
## Code Overview
## Foundry Setup
## Basic NFT
### Write Tests 
- Openzeppelin NFT
## IPFS NFT
### Setting an NFT Mint Price
### Deploy Script
### Uploading Token Images with Pinata
- Pinata
- nft.storage
- Pinata NPM
- Pinata Docs
### Uploading Token URIs (metadata) with Pinata
### Deploying
### Tests
## SVG On-Chain NFT
- Patrick's Original Video
### What is an SVG?
- SVG Tutorial
  - On-Chain SVG Example
### Initial Code  
### Base64 Encoding
- Base64 Encoding
  - Example Encoder
- base64-sol
## Advanced: EVM Opcodes, Encoding, and Calling
### abi.encode & abi.encodePacked
- abi.encode
- abi.encodePacked
Thanks to [Alex Roan](https://twitter.com/alexroan) for his help on this session!
- Example Contract Creation Transaction
What REALLY is the ABI?
- EVM Opcodes
- More EVM Opcodes
- Solidity Cheatsheet
- abi.encode vs abi.encodePacked
### Introduction to Encoding Function Calls Directly
### Introduction to Encoding Function Calls Recap
### Encoding Function Calls Directly
- Function Selector
- Function Signature
### Creating an NFT TokenURI on-Chain
### Deploy Script
## Deploying the NFTs to a Testnet
## Lesson 12 Recap
- [ENS](https://ens.domains/)

# Lesson 12: Foundry DeFi | Stablecoin (The PINNACLE PROJECT!! GET HERE!)

💻 Code: [https://github.com/ChainAccelOrg/foundry-defi-stablecoin-f23](https://github.com/ChainAccelOrg/foundry-defi-stablecoin-f23)

## What is DeFi?
- [What is DeFi?](https://chain.link/education/defi)
- [DefiLlama](https://defillama.com/)
## What is Aave?
- [Aave](https://aave.com/)
- [My Previous Aave Video on Shorting Assets](https://www.youtube.com/watch?v=TmNGAvI-RUA)
## Programmatic Borrowing & Lending
- [DAI](https://makerdao.com/en/)
- [Uniswap](https://app.uniswap.org/)
## WETH - Wrapped ETH
- [WETH Token Sepolia Etherscan](https://sepolia.etherscan.io/address/0xdd13E55209Fd76AfE204dBda4007C227904f0a81)
- [WETH Token Mainnet](https://etherscan.io/token/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2)
## Depositing into Aave
- [Aave V2 Docs](https://docs.aave.com/developers/v/2.0/)
- [Aave NPM](https://www.npmjs.com/package/@aave/protocol-v2)
## Borrowing from Aave
- [Aave Borrowing FAQs](https://docs.aave.com/faq/borrowing)
- [Health Factor](https://docs.aave.com/faq/borrowing#what-is-the-health-factor)
- [Aave Risk Parameters](https://docs.aave.com/risk/asset-risk/risk-parameters)
## Repaying with Aave 
## Visualizing the Transactions
- [aTokens](https://docs.aave.com/developers/v/1.0/developing-on-aave/the-protocol/atokens)
## MEV
- [Maximal Extractable Value](https://ethereum.org/en/developers/docs/mev/)
- [FlashBots new to MEV](https://docs.flashbots.net/new-to-mev)
## Smart Contract Audit
- [What is a smart contract audit](https://www.youtube.com/watch?v=aOqhQvWhUG0)
## What is a stablecoin?
- [Stablecoins, but actually](https://www.youtube.com/watch?v=pciVQVocTYc)
## Fuzzing
- [Fuzzing intro](https://www.youtube.com/watch?v=juyY-CTolac)

## Happy Bow-Tie Friday with Austin Griffith
- [Special Guest Austin Griffith](https://twitter.com/austingriffith)!
- [Speed Run Ethereum](https://speedrunethereum.com/) 
### More DeFi Learnings: 
- [Defi-Minimal](https://github.com/smartcontractkit/defi-minimal/tree/main/contracts)
- [Defi Dad](https://www.youtube.com/channel/UCatItl6C7wJp9txFMbXbSTg)

# Lesson 13: Foundry Upgrades

💻 Code: [https://github.com/ChainAccelOrg/foundry-upgrades-f23](https://github.com/ChainAccelOrg/foundry-upgrades-f23)

## Upgradable Smart Contracts Overview
- [Optional Video](https://www.youtube.com/watch?v=bdXJmWajZRY)
## Types of Upgrades
1.  Parameter
2.  Social Migrate
3.  Proxy
    1.  Proxy Gotchas
        1. [Function Collisions](https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/#diamonds)
        2. [Storage Collisions](https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/#diamonds)
    2.  [Metamorphic Upgrades](https://github.com/PatrickAlphaC/hardhat-metamorphic-upgrades-fcc)
    3.  [Transparent](https://blog.openzeppelin.com/the-transparent-proxy-pattern/)
    4.  [UUPS](https://forum.openzeppelin.com/t/uups-proxies-tutorial-solidity-javascript/7786)
    5.  [Diamond](https://eips.ethereum.org/EIPS/eip-2535)
## Delegatecall
- [delegatecall (solidity-by-example)](https://solidity-by-example.org/delegatecall)
- [Yul](https://docs.soliditylang.org/en/latest/yul.html)
## Small Proxy Example
- [EIP 1967](https://eips.ethereum.org/EIPS/eip-1967)
## Universal Upgradable Smart Contract 
- [UUPS vs Transparent](https://docs.openzeppelin.com/contracts/4.x/api/proxy#transparent-vs-uups)
- [Hardhat-deploy Proxies](https://github.com/wighawag/hardhat-deploy#deploying-and-upgrading-proxies)

# Lesson 14: Foundry DAO / Governance 

Plutocracy is bad! Don't default to ERC20 token voting!!

💻 Code: [https://github.com/ChainAccelOrg/foundry-dao-f23](https://github.com/ChainAccelOrg/foundry-dao-f23)

## Introduction
## What is a DAO?
- [What is a DAO?](https://www.youtube.com/watch?v=X_QKZzd68ro)
## How to build a DAO
- [How to build a DAO](https://www.youtube.com/watch?v=AhJtmUqhAqg)
- That's Patrick
- [PY Code](https://github.com/brownie-mix/dao-mix)
- [Python Video](https://www.youtube.com/watch?v=rD8AxZ_wBA4)
- [Openzeppelin Governance](https://docs.openzeppelin.com/contracts/4.x/api/governance)
- [Compound Governance](https://compound.finance/governance)
- [Contract Wizard](https://docs.openzeppelin.com/contracts/4.x/wizard)
- [CastVoteBySig](https://forum.openzeppelin.com/t/what-is-votecastbysig/17069/2)

# Lesson 15: Smart Contract Security & Auditing (For developers)

Developers 100% should know all about this! Don't leave the course without at least watching this section!

- Reentrancy
- Symbolic Execution
- Flash loans
