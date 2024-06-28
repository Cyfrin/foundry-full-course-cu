This markdown file is a list of improvements to the zkSync developer experience environment. 

> [!IMPORTANT]  
> It is our opinion that at the moment, certain aspects of the zkSync ecosystem are not ready for production use. The list here itemizes situations where we do not recommend you deploy to zkSync. Below each situation is a list of check boxes, that once filled, we believe the situation is ready for production use. The developer experience for each of the following makes the experience so poor, that we don't want developers making hacky work-arounds that may cause them to make mistakes. 

# 1. Using is-system/system-mode contracts should not be used for production (hardhat or zkSync)
- [ ] verification for explorers must work that interact with system contracts

Github Issue: https://github.com/matter-labs/foundry-zksync/issues/102

## Rationale 
Being able to see the actual solidity code in the explorer is crucial for understanding what code people are going to be interacting with. Rug-pullers can essentially say "trust me bro, we can't verify on zkSync so we had to leave it as raw assembly" which is going to get a lot of people hurt. As of today, it's not possible to verify `is-system` or `system-mode=true` contracts on zkSync.

# 2. Using foundry as your deployment framework should not be used for production
- [ ] foundry-zksync scripting must first work for deployment 
- [ ] local tests run with `--zksync` must first all work, with cheatcodes 
- [ ] foundry-zksync must be able to verify smart contracts

Github Issues: 
- https://github.com/matter-labs/foundry-zksync/issues/408
- https://github.com/matter-labs/foundry-zksync/issues/389

## Rationale 
You *must* be able to test your deploy process. Full stop. As of today, the foundry cheat codes and tests are not compatible. There is a work around where a users testing process involves running a local zkSync node, and uses bash scripts to deploy and run their tests, but that sort of starts to defeat the purpose of using foundry in the first place. And again, foundry needs to be able to verify smart contracts for the same reason as above. 

# 3. Using cast as your bash scripting framework should not be used for production if you're looking to make account abstraction contracts
- [ ] foundry-zksync contract creation must first work for `create`, `create2`, `createAccount`, and `create2Account`

Github Issues:
- https://github.com/matter-labs/foundry-zksync/issues/434

## Rationale
foundry-zksync as of today has no way to create account abstraction compatible contracts, either via cast or forge. This is due to having to set `factoryDeps` alongside your transaction to the `CONTRACT_DEPLOYER` system contract, and should be fixed before production use. 

# 4. Using any library or tooling from the era-contracts/zksync-contracts repo should not be used for production
- [ ] The [npm package zksync-contracts](https://www.npmjs.com/package/@matterlabs/zksync-contracts) must be clear about what they do, and where they are from. There are also several other issues with the package that should be addressed as well. 

Github Issues:
- https://github.com/matter-labs/era-contracts/issues/457
- https://github.com/matter-labs/era-contracts/issues/438
- Not a GitHub issue, but this package should be clearer: https://www.npmjs.com/package/@matterlabs/zksync-contracts

## Rationale
The current [zksync-contracts](https://www.npmjs.com/package/@matterlabs/zksync-contracts) npm packages is currently recommended in the zkSync documentation, however it's very unclear what code it is using and how to contribute. At the moment, this lack of clarity could be considered a security issue, as the code was published a year ago and the zkSync chain has changed a lot since then. In the future, the [era-contracts](https://github.com/matter-labs/era-contracts) should replace it

# 5. Using 5.0.0+ of openzeppelin libraries and hardhat 
- [ ] The dependency on specific openzeppelin packages should be removed for zksync libraries.

Github Issues:
- https://github.com/matter-labs/era-contracts/issues/438

## Rationale
Many hardhat libraries are hard-pegged to specific versions of openzeppelin libraries, typically one of the 4+ versions. This makes it challenging to have smart contracts in a hardhat environment. 

# 6. Don't use the zkSync remix plugin
- [ ] The plugin fails to:
  - [ ] Verify certain contracts (likely same issues as above)
  - [ ] Verify contracts with libraries
  - [ ] Auto detech the correct solidity and zkSolc version (like the solidity compiler does)

GitHub Issues:
- https://github.com/NethermindEth/zksync-remix-plugin/issues/110

## Rationale
You shouldn't really be using remix for serious projects anyways, but the plugin's seemingly difficulty working with smart contracts is enough erosion to the developer experience that I don't trust using it. 