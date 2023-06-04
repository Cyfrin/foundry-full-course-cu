*This repo is a work in progress*

# Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023

Welcome to the repository for the Blockchain Developer, Smart Contract, & Solidity Course | Powered By AI | Beginner to Expert Course | Foundry Edition 2023

*Video coming soon...*

## Recommended Tools
- Recommended Testnet: Sepolia
- Recommended DevOps: [foundry-devops](https://github.com/Cyfrin/foundry-devops)

# [Testnet Faucets](https://faucets.chain.link)
- Main Faucet:<a href="https://faucets.chain.link" target="_blank"> https://faucets.chain.link</a>
- Backup Faucet:<a href="https://sepoliafaucet.com/" target="_blank"> https://sepoliafaucet.com/</a>

> ⚠️ All code associated with this course is for demo purposes only. They have not been audited and should not be considered production ready. Please use at your own risk. 

# Resources For This Course

- AI Frens
  - [ChatGPT](https://chat.openai.com/)
      - Just know that it will often get things wrong, but it's very fast!
  - [Phind](https://www.phind.com/)
      - Like ChatGPT, but it searches the web
  - [Bard](https://bard.google.com/)
  - [Other AI extensions](https://twitter.com/aisolopreneur/status/1654823630155464704?s=42&t=-pu_sCYtfrfPJU7OXfifrQ)
- Github Discussions 
    -   Ask questions and chat about the course here!
-   [Stack Exchange Ethereum](https://ethereum.stackexchange.com/)
    -   Great place for asking technical questions about Ethereum
-   [Peeranha](https://peeranha.io/)
    -   Decentralized Stack Exchange!


New: Each lesson gets an NFT, and a "where to learn more" section. Maybe on ZKSync? Have a section be "moving funds to an L2". 

TODO: 
- Update repo gitpods.
- Double check repos are using `cyfrin` and not `patrickalphac` in the repos. 

<!-- - [Blockchain Developer, Smart Contract, \& Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023](#blockchain-developer-smart-contract--solidity-course---powered-by-ai---beginner-to-expert-course--foundry-edition-2023)
  - [Recommended Tools](#recommended-tools)
- [Testnet Faucets](#testnet-faucets)
- [Resources For This Course](#resources-for-this-course)
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
  - [Introduction](#introduction-2)
  - [Static Analysis](#static-analysis)
    - [Slither](#slither)
  - [Dynamic Analysis](#dynamic-analysis)
    - [Unit, Integration, Staging Tests](#unit-integration-staging-tests)
    - [Fuzzing](#fuzzing-1)
    - [Formal Verification (\& Symbolic Execution)](#formal-verification--symbolic-execution)
  - [Closing Thoughts](#closing-thoughts)
- [Congratulations](#congratulations)
  - [Where do I go now?](#where-do-i-go-now)
    - [Learning More](#learning-more)
    - [Community](#community)
    - [Hackathons](#hackathons)
- [Disclosures](#disclosures)
- [Thank you](#thank-you) -->


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
- 

# Lesson 2: Welcome to Remix - Remix Simple Storage

💻 Code: [https://github.com/cyfrin/remix-simple-storage-f23](https://github.com/cyfrin/remix-simple-storage-f23)

## AI Help II

## TODO: Extra credit / Exersizes!

1. Deploy a contract to <L2>

# Lesson 3: Remix Storage Factory

💻 Code: [https://github.com/cyfrin/remix-storage-factory-f23](https://github.com/cyfrin/remix-storage-factory-f23)

## Intro
## Setup
## Deploying a contract from a contract
## Imports
## AI Help I
## ABI
## Inheritance
- `virtual` and `override` keyword
## Summary

## TODO: Extra credit / Exersizes!

1. Deploy a contract to <L2>

# Lesson 4: Remix Fund Me

💻 Code: [https://github.com/Cyfrin/remix-fund-me-f23](https://github.com/Cyfrin/remix-fund-me-f23)

## Introduction
## Setup
## Sending ETH through a function
- `Payable` 
- [Fields in a transaction]() 
- `msg.value`
- [globally availible keywords]()
- [require]()
- [wei vs ETH vs gwei]
## Reverts   
## Getting real world price data (Chainlink)
## Quick recap I
## Interfaces
## AI Help III
## Importing from NPM / GitHub
## Getting Prices from Chainlink
## More solidity math
- Multiply before you divide
## msg.sender
- msg.sender
- named mappings
## Quick recap II
## Library
- [Solidity by example](https://solidity-by-example.org/library/)
## SafeMath
## For Loop
- `/* */` is another way to make comments
## Resetting an array
## Transfer, Send, and Call
- [Solidity by Example]()
## Constructor
## Modifiers
## Testnet Demo
## Advanced Solidity 
### Immutable & Constant
- [Immutable](https://solidity-by-example.org/immutable)
- [Constant](https://solidity-by-example.org/constants)
- [Current ETH Gas Prices](https://etherscan.io/gastracker)
- Don't stress about gas optimizations! (yet)
- Naming Conventions
  - [Someone make this!](https://github.com/smartcontractkit/full-blockchain-solidity-course-js/issues/13)

### Custom Errors
- [Custom Errors Introduction](https://blog.soliditylang.org/2021/04/21/custom-errors/)

### Receive & Fallback Functions
- [Solidity Docs Special Functions](https://docs.soliditylang.org/en/latest/contracts.html?highlight=fallback#special-functions)
- [Fallback](https://solidity-by-example.org/fallback)
- [Receive](https://docs.soliditylang.org/en/latest/contracts.html?highlight=fallback#receive-ether-function)

## TODO: Extra credit / Exersizes!
Deploy to L2

# Lesson 5: AI Prompting, Asking Questions, and Getting Help

DO NOT SKIP THIS!!

## Intro
- [Deep Learning for Python Engineers]()
## 7 Tips for this Course
## Setting up GitHub
## Formatting a question
- [markdown]()

* It's a good idea to ask your AI buddy to format your questions in markdown *

## SpeedRunEthereum
- Special Guest [Austin](https://twitter.com/austingriffith)


# Lesson 6: Foundry Simple Storage

💻 Code: [https://github.com/Cyfrin/foundry-simple-storage-f23](https://github.com/Cyfrin/foundry-simple-storage-f23)

## Introduction
## Installation & Setup (MacOS & Linux)
-   [Visual Studio Code](https://code.visualstudio.com/)
    - [Crash Course](https://www.youtube.com/watch?v=WPqXP_kLzpo)
- [VSCode Keybindings](https://code.visualstudio.com/docs/getstarted/keybindings)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [What is a terminal?](https://code.visualstudio.com/docs/editor/integrated-terminal)

### Windows Setup
- Special Guest [Vasiliy](https://twitter.com/cromewar)
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
  

## Foundry Install
- [https://getfoundry.sh](https://getfoundry.sh)
## VSCode Setup II
- CoPilot
- Copilot labs
- Hardhat Solidity Extension
- VSCodium
- `mkdir foundry-f23`
## Foundry Setup
- FreeCodeCamp Bash 

## Formatting Solidity in VSCode
- Format your solidity code with in your `settings.json`
```json
    "[solidity]": {
        "editor.defaultFormatter": "NomicFoundation.hardhat-solidity"
    },
    "[javascript]":{
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
```
## Compiling in Foundry
## Deploying to a local chain I (Anvil or Ganache)
- [Ganache](https://trufflesuite.com/ganache/)
## Adding another network to metamask
- [ETH JSON RPC](https://ethereum.github.io/execution-apis/api-documentation/)
## Deploying to a local chain II (Forge Create)
- 2 Ways to deploy:
  - 1. `forge create`
  - 2. `forge script`

## Private Key Rant I
- `history -c`

## Deploying to a local chain III (Forge Script)
## What is a transaction (But actually)
```bash
cast --to-base 0x01 dec
```
## Private Key R ant II
- `cast send`
- `source .env`

# Can you Encrypt a Private Key -> a keystore in foundry yet??
A: No
- [The .env pledge]()

## ThirdWeb Deploy
- Special Guest [Ciara](https://twitter.com/CiaraNightingal)
- [nodejs install]()
- [npm install]()
- [thirdweb]()

## Private Key Rant Summary:
```
Summary:
When you look to deploy 
with real money, you should use either:
1. A password encrypted keystore
2. Something like thirdweb deploy

The idea is you never want to have 
your private key or password 
ANYWHERE written in plain text
(Aka, you always want it encrypted)
```
- [Someone fix this please](https://github.com/foundry-rs/foundry/issues/3818)

## Cast Send

## Deploying to a testnet or a mainnet
- [Alchemy](https://alchemy.com/?a=673c802981)
- Other node as a service:
  - [Quicknode]()
  - [Infura]()

## Verifying a contract the manual way
- [Example verified contract](https://sepolia.etherscan.io/address/0xe2e9f468eb7f063aa01670bb4bce4119fb6e4b65#code)

## Cleaning up the project
- `forge fmt`
- `README.md`
- [markdown]()

## Alchemy
- Special Gust [Vitto](https://twitter.com/VittoStack)
- [Alchemy](https://alchemy.com/?a=673c802981)

## Summary

## TODO: Add FCC bash lessons

## TODO: Extra credit / Exersizes!
Deploy to L2

# Lesson 7: Foundry Fund Me

💻 Code:[https://github.com/Cyfrin/foundry-fund-me-f23](https://github.com/Cyfrin/foundry-fund-me-f23)
## Introduction 

## Setup

## Testing Introduction

## Setup Continued
- [Dependencies](https://book.getfoundry.sh/projects/dependencies)
- [remappings]()

## Tests
- [foundry tests]()
- [console.log]()

## Debugging Tests I

## Advanced Deploy Scripts I

## Forked Tests
-  4 types of testing:
```
1. Unit: Testing a single function
2. Integration: Testing multiple functions
3. Forked: Testing on a forked network
4. Staging: Testing on a live network (testnet or mainnet)
```
- [forking in foundry]()
- [forge coverage]()

## Refactoring I: Testing Deploy Scripts

## Refactoring II: Helper Config
- [block.chainid]()
- [Chain ID List](https://chainlist.org/)
  - 11155111 is ETH Sepolia
  - 1 is ETH Mainnet

## Refactoring III: Mocking (continued)
- [Mocking](https://stackoverflow.com/questions/2665812/what-is-mocking)
- [Chainlink Github](https://github.com/smartcontractkit/chainlink)
- Multiple Versions of Solidity

## Magic Numbers
- [Style Guide]()
- [Magic Numbers]()

# Break time!
*****
Take a break!
*****

## More Cheatcodes
- [foundry cheatcodes]()
- [forge std cheats]()
  - [vm.expectRevert]()
  - [vm.prank]()
  - [makeAddr]()
  - [deal]()

## More Coverage
- [State tree testing](https://twitter.com/PaulRBerg/status/1624763320539525121?s=20)
- Arrange, Act, Assert
- [hoax]()
- [uint160 -> address]()
- [vm.startPrank]()

## Chisel 

## Gas: Cheaper Withdraw
- [Gas Reporter](https://book.getfoundry.sh/forge/gas-reports)
- [forge snapshot]()
- [vm.txGasPrice]()
- [gasLeft()]()
- [tx.getprice]()

## Storage 
** Advanced **
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

## Gas: Cheaper Withdraw (continued)
- [evm.codes]()
- [Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html)
  - [Chainlink Style Guide](https://github.com/smartcontractkit/chainlink/blob/develop/contracts/STYLE.md)
- [NatSpec](https://docs.soliditylang.org/en/latest/natspec-format.html)

## Interactions.s.sol
- [foundry devops]()
- [Best README Template]()
- [ffi]()

## Makefile
- [Install make]()
- [Etherscan API Key](https://docs.etherscan.io/getting-started/viewing-api-usage-statistics)

## Pushing to GitHub
- Add these to your `.gitignore`
  - `.env`
  - `lib/`
  - `broadcast/`
- [Git Docs](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [GitHub docs](https://docs.github.com/en)
- [Github Quickstart](https://docs.github.com/en/get-started/quickstart)
- [What is Git?](https://www.git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
- [The quickstart that we follow in the video](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#adding-a-local-repository-to-github-using-git)
- [Learn about git and GitHub](https://www.youtube.com/watch?v=RGOj5yH7evk)

## 🐸🐦 [Tweet Me (add your repo in)!](https://twitter.com/intent/tweet?text=I%20just%20made%20my%20first%20Smart%20Contract%20repo%20using%20@solidity_lang,%20foundry,%20@chainlink,%20@AlchemyPlatform,%20and%20more!%0a%0aThanks%20@PatrickAlphaC!!)

## Recap

# Lesson 8: Html/Js Fund Me (Quick Fullstack / Front End Tutorial)

💻 Code: [https://github.com/Cyfrin/html-fund-me-f23](https://github.com/Cyfrin/html-fund-me-f23)

- [More in-depth Javascript & Full Stack introduction video](https://www.youtube.com/watch?v=pdsYCkUWrgQ)

## Introduction
## Setup
- [Live Server Extension]()

## How metamask works with your browser
- [Metamask Docs]()
- [Ethers Docs]()

## Introduction to function selectors
- [Function selector](https://ethereum.stackexchange.com/questions/49996/what-is-the-function-selector-of-the-fallback-function?rq=1)
- [cast sig](https://book.getfoundry.sh/reference/cast/cast-sig?highlight=sig#cast-sig)

## Recap

- [More in-depth Javascript & Full Stack introduction video](https://www.youtube.com/watch?v=pdsYCkUWrgQ)

# Lesson 9: Foundry Smart Contract Lottery

💻 Code: [https://github.com/Cyfrin/foundry-smart-contract-lottery-f23](https://github.com/Cyfrin/foundry-smart-contract-lottery-f23)

## Introduction

## Raffle.sol Setup
* Raffle.sol Setup

## Solidity Contract Layout
- [Layout Style Guide]()

## Custom Errors
- Custom Errors in Solidity

## Events
* Introduction to Events
- Events & Logging Video
- Events & Logging in Hardhat
## block.timestamp
## Chainlink VRF
* Introduction to Chainlink VRF
- Special Guest [Richard](https://twitter.com/RGottleber)
### Sub-Lesson: Chainlink VRF
> - Chainlink VRFv2 Docs
> - Chainlink VRFv2 Walkthrough
> - Chainlink Contracts
## Implementing Chainlink VRF - Introduction
* Implementing Chainlink VRF
## Implementing Chainlink VRF - The Request
## Implementing Chainlink VRF - The FulFill
## Chainlink VRF Recap

### Modulo
- Modulo

## Enum
## Resetting an array
## Note on building 
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
## Mid-Lesson Recap
## Tests & Deploy Script Setup
### Mock Chainlink VRF Coordinator
## Tests & Deploy Script Continued
## Lots of Tests
### Testing Events in Foundry
### vm.roll & vm.warp
## Create Subscription Script
- [eth signature database](https://openchain.xyz/signatures)
## Create Subscription from the UI
## Fund Subscription Script
- [Link Token]()
- [Solmate]()
- [Openzeppelin]()
## Add Consumer Script
- [FoundryDevops]()
## More Tests
- `forge coverage --report debug`
## PerformUpkeep Tests
- Expecting Custom Errors 
## Getting Event Data into Foundry Scripts
- `vm.recordLogs`
## Intro to Fuzz tests
## One Big Test
## Passing the private key to vm.startBroadcast
## Integrations Test
## Testnet Demo - Makefile setup
## Testnet Demo - The Demo
## Console.log Debugging
## forge test --debug
## Recap

### Recommended LINK amounts for Sepolia Staging Test:
- Chainlink VRF: 2 LINK
- Chainlink Keepers: 8 LINK

# Lesson 10: Foundry ERC20s

💻 Code: [https://github.com/Cyfrin/foundry-erc20-f23](https://github.com/Cyfrin/foundry-erc20-f23)

## What is an ERC? What is an EIP?
- What is an EIP?
- EIPs codebase
## What is an ERC20?
- [Video (using brownie/python)](https://www.youtube.com/watch?v=8rpir_ZSK1g)
- EIP-20
- ERC-677
- EIP-777
## Manually Creating an ERC20 Token
- `.github`
## ERC20 Token - Openzeppelin
- Openzeppelin
  - [Openzeppelin Wizard]()
- Openzeppelin Contracts
- Solmate (Openzeppelin alternative)
## Deploy Script
## AI Tests
- [Token Approvals]()
## Lesson 12 Recap


# Lesson 11: Foundry NFTs | MoodNFT

💻 Code: [https://github.com/Cyfrin/foundry-nft-f23](https://github.com/Cyfrin/foundry-nft-f23)

## Introduction
## What is an NFT? 
- Video
- Optional: All on Chain SVG NFT
- EIP-721
## Foundry Setup
- TokenURI
- Pudgy Penguin Example
## IPFS
- [What is IPFS](https://www.youtube.com/watch?v=5Uj6uR3fp-U)
## Using IPFS
## Basic NFT: Deploy Script
## Basic NFT: Tests
- Comparing strings in solidity
- `chisel`
## Basic NFT: Interactions
## Basic NFT: Testnet Demo
## The issue with IPFS & HTTPS TokenURI NFTs
- [pinata](https://pinata.cloud/)
- [SVG NFT Video]()
## What is an SVG?
- [svg]()
- [vscode extension]()
- [base64 encoding]()
## SVG NFT: Introduction
## SVG NFT: Encoding the NFT
- [base64 openzeppelin]()
## SVG NFT: Flipping the mood
## SVG NFT: Deploy Script
- [readFile Cheat]()
## SVG NFT: Debugging practice & some notes
## SVG NFT: Anvil Demo
- [arweave]()
- [fileweave]()
- [nft.storage]()
- [Patrick video on Filecoin]()
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
## Verifying Metamask Transactions
1. Check the address
2. Check the function selector
3. Decode the calldata
- [joinfire.zxyz]()
## Filecoin & Arweave
- Special Guest [Ally](https://twitter.com/DeveloperAlly)
## Lesson 12 Recap
- [ENS](https://ens.domains/)

# Lesson 12: Foundry DeFi | Stablecoin (The PINNACLE PROJECT!! GET HERE!)

💻 Code: [https://github.com/Cyfrin/foundry-defi-stablecoin-f23](https://github.com/Cyfrin/foundry-defi-stablecoin-f23)

## What is DeFi?
- [What is DeFi?](https://chain.link/education/defi)
- [DefiLlama](https://defillama.com/)
- [Bankless]()
- [MEV](https://www.flashbots.net/)
- [Aave](https://aave.com/)
- [My Previous Aave Video on Shorting Assets](https://www.youtube.com/watch?v=TmNGAvI-RUA)
- [DAI](https://makerdao.com/en/)
- [Uniswap](https://app.uniswap.org/)
- [Maximal Extractable Value (MEV)](https://ethereum.org/en/developers/docs/mev/)
## Code Walkthrough
- [What is a smart contract audit](https://www.youtube.com/watch?v=aOqhQvWhUG0)
## What is a stablecoin (But actually)
- [Video](https://www.youtube.com/watch?v=pciVQVocTYc)
- [MakerDAO Forums]()
## DecentralizedStableCoin.sol
- [What is a smart contract audit](https://www.youtube.com/watch?v=aOqhQvWhUG0)
- `super`
## DSCEngine.sol Setup
- [liquidations]()
- [nonreentrant]()
  - [reentrancy]()
## Deposit Collateral
- Other DeFi Examples:
  - [Aave V2 Docs](https://docs.aave.com/developers/v/2.0/)
  - [Aave NPM](https://www.npmjs.com/package/@aave/protocol-v2)
## Mint DSC
### Getting the value of our collateral
- [Aave Borrowing FAQs](https://docs.aave.com/faq/borrowing)
- [Health Factor](https://docs.aave.com/faq/borrowing#what-is-the-health-factor)
- [Aave Risk Parameters](https://docs.aave.com/risk/asset-risk/risk-parameters)
### Health Factor
- [Liquidation Threshold]()
### Minting the DSC
## Testing while developing
### Deploy Script
- [WETH Token Sepolia Etherscan](https://sepolia.etherscan.io/address/0xdd13E55209Fd76AfE204dBda4007C227904f0a81)
- [WETH Token Mainnet](https://etherscan.io/token/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2)
### Tests
## depositCollateralAndMintDsc
## redeemCollateral
## Liquidate
### Setup
### Refactoring
## Leveling up your testing skillz 
## Challenge: Code coverage above 80% for DSCEngine.sol
## Fuzz (Invariant) Testing
- [Video](https://www.youtube.com/watch?v=juyY-CTolac)
## Open-based Fuzz tests
## Handler-based Fuzz tests
### revert_on_fail = true
### Redeeming Collateral
### Minting DSC
### Debuggin Fuzz Tests
- [Ghost Variables]()
### Challenge: Find out why `mintDsc` is never being called on our Handler.sol
## Price Feed Handling
## OracleLib
## Note on audit preparedness
- [Simple security checklist]()
## Recap
## Lens Protocol
- Special Guest [Nader](https://twitter.com/dabit3)
- [Lens Protocol](https://www.lens.xyz/)

### More DeFi Learnings: 
- [Defi-Minimal](https://github.com/smartcontractkit/defi-minimal/tree/main/contracts)
- [Defi Dad](https://www.youtube.com/channel/UCatItl6C7wJp9txFMbXbSTg)

# Lesson 13: Foundry Upgrades

💻 Code: [https://github.com/Cyfrin/foundry-upgrades-f23](https://github.com/Cyfrin/foundry-upgrades-f23)

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
### Setup
- [UUPS vs Transparent](https://docs.openzeppelin.com/contracts/4.x/api/proxy#transparent-vs-uups)
- Abstract Contracts
### Initializer
### Deploy
- [ERC-1967]()
### UpgradeBox
### Test / Demo
## Testnet Demo


# Lesson 14: Foundry DAO / Governance 

Plutocracy is bad! Don't default to ERC20 token voting!!

💻 Code: [https://github.com/Cyfrin/foundry-dao-f23](https://github.com/Cyfrin/foundry-dao-f23)

## Introduction
- [Plutacray is bad](https://vitalik.ca/general/2018/03/28/plutocracy.html)
- [DAOs are not corporations](https://vitalik.ca/general/2022/09/20/daos.html)
## What is a DAO?
- [What is a DAO?](https://www.youtube.com/watch?v=X_QKZzd68ro)
- Special Guest [Juliette](https://twitter.com/_juliettech)
## How to build a DAO
### Setup
- [How to build a DAO](https://www.youtube.com/watch?v=AhJtmUqhAqg)
- That's Patrick
- [PY Code](https://github.com/brownie-mix/dao-mix)
- [Python Video](https://www.youtube.com/watch?v=rD8AxZ_wBA4)
### Governance Token
- [Openzeppelin Governance](https://docs.openzeppelin.com/contracts/4.x/api/governance)
- [Compound Governance](https://compound.finance/governance)
- [Contract Wizard](https://docs.openzeppelin.com/contracts/4.x/wizard)
### Governor
- [CastVoteBySig](https://forum.openzeppelin.com/t/what-is-votecastbysig/17069/2)
### Tests
## Wrap up
## Bonus: Gas optimization tips
- Special Guest [Harrison](https://twitter.com/PopPunkOnChain)

# Lesson 15: Smart Contract Security & Auditing (For developers)

Developers 100% should know all about this! Don't leave the course without at least watching this section!

🖥️ Code: https://github.com/PatrickAlphaC/denver-security

## Introduction
- [Readiness Checklist](https://github.com/nascentxyz/simple-security-toolkit)
## What is a smart contract audit?
- [What is a smart contract audit]()
## What does the process of manual review look like? 
- [Tincho finds $100,000 ENS bug]()
## Tools
### Manual Review
### Static Analysis
- [Slither](https://github.com/crytic/slither#how-to-install)
- [4nlyzer](https://github.com/Picodes/4naly3er)
### Dynamic Analysis
### Formal Verification
### Symbolic Execution
- [Manticore](https://github.com/trailofbits/manticore)
- [Mythril](https://github.com/ConsenSys/mythril)
- [hevm](https://github.com/ethereum/hevm)
- [Comparison](https://hackmd.io/@SaferMaker/EVM-Sym-Exec)
### Fuzzing
- [Echidna](https://github.com/crytic/echidna)
- [Foundry](https://getfoundry.sh/)
- [Consensys](https://fuzzing.diligence.tools/login)
### Formal Verification (& Symbolic Execution)
- [Comparisons](https://twitter.com/palinatolmach/status/1653030270684270592)
### Other security stuff
- [solcurity](https://github.com/transmissions11/solcurity)
## Closing Thoughts
-   [Best Practices](https://consensys.github.io/smart-contract-best-practices/)
-   [Attacks](https://consensys.github.io/smart-contract-best-practices/attacks/)
    -   [Oracle Attacks](https://hackernoon.com/how-dollar100m-got-stolen-from-defi-in-2021-price-oracle-manipulation-and-flash-loan-attacks-explained-3n6q33r1)
-   [Damn Vulnerable Defi](https://www.damnvulnerabledefi.xyz/)
-   [Ethernaut](https://ethernaut.openzeppelin.com/)
-   [Top Smart Contract Auditors](https://patrickalphac.medium.com/top-7-smart-contract-auditors-bec7bd70dd9f)
-   Some Smart Contract Auditors:
    -   [Cyfrin](https://cyfrin.io/)
    -   [OpenZeppelin](https://openzeppelin.com/)
    -   [SigmaPrime](https://sigmaprime.io/)
    -   [Trail of Bits](https://www.trailofbits.com/)
    -   [Spearbit](https://spearbit.com/)
    -   [Dedaub](https://dedaub.com/)
    -   [Trust](https://www.trust-security.xyz/)
    -   [More](https://patrickalphac.medium.com/top-7-smart-contract-auditors-bec7bd70dd9f)

# Congratulations

🎊🎊🎊🎊🎊🎊🎊🎊🎊🎊🎊🎊 Completed The Course! 🎊🎊🎊🎊🎊🎊🎊🎊🎊🎊🎊🎊 

## Where do I go now?

### Learning More

- [Top 10 learning resources](https://patrickalphac.medium.com/top-10-smart-contract-solidity-developer-learning-resources-cb9d60dd1146)
-   [Patrick Collins](https://www.youtube.com/channel/UCn-3f8tw_E1jZvhuHatROwA)
-   [CryptoZombies](https://cryptozombies.io/)
-   [Alchemy University](https://www.alchemy.com/dapps/alchemy-university)
-   [Speed Run Ethereum](https://speedrunethereum.com/)
-   [Ethereum.org](https://ethereum.org/en/)

### Community

-   [Twitter](https://twitter.com/PatrickAlphaC)
-   [Chainlink Discord](https://discord.gg/2YHSAey)
-   [Ethereum Discord](https://ethereum.org/en/)
-   [Reddit ethdev](https://www.reddit.com/r/ethdev/)

### Hackathons

-   [CL Hackathon](https://chain.link/hackathon)
-   [ETH Global](https://ethglobal.co/)
-   [ETH India](https://twitter.com/ETHIndiaco)

Be sure to check out project grant programs!

And make today an amazing day!

# Disclosures

Transparency is important! So we want to disclouse any potential conflicts that might have affeted my judgement so you can pick tools that are right for you. Patrick is co-founder of Alpha Chain, a blockchain infrastructure company. Alpha Chain runs **chainlink, ethereum, binance, polygon, harmony, solana, moonbeam, and moonriver blockchain services.** Alpha Chain often works with Alchemy and recieves discounted servies. Patrick is co-founder of Cyfrin, and they do smart contract security & auditing services. Patrick is a co-founder of Chain Accel, who are an advisor on the Peeranha project. Patrick is an advisor on the Chainlink project. The Cyfrin team often does buisness on the Arbitrum L2. 

Because of all this, I have added alternatives to each section where we suggest a tool. This video & course was created and sponsored solely by the [Cyfrin](https://www.cyfrin.io/) team. 

# Thank you

Thanks to everyone who is taking, participating in, and working on this course. It's been a passion project and a data dump of everything I've learnt in the web3 space to get you up to speed quickly. Also, a big thank you to Cyfrin & Chain Accel for encouraging this course to come to light, and many, many, many people from the community. 

[![Patrick Collins Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/PatrickAlphaC)
[![Patrick Collins YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCn-3f8tw_E1jZvhuHatROwA)
[![Patrick Collins Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/patrickalphac/)
[![Patrick Collins Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@patrick.collins_58673/)

