This markdown file is a list of improvements to the zkSync developer experience environment. 

> [!IMPORTANT]  
> It is our opinion that at the moment, certain aspects of the zkSync ecosystem are not ready for production use. The list here itemizes situations where we do not recommend you deploy to zkSync. Below each situation is a list of check boxes, that once filled, we believe the situation is ready for production use.


# 1. Using is-system/system-mode contracts should not be used for production (hardhat or zkSync)
- [ ] verification for explorers must work that interact with system contracts

# 2. Using foundry as your deployment framework should not be used for production
- [ ] foundry-zksync scripting must first work for deployment 
- [ ] local tests run with `--zksync` must first all work, with cheatcodes 
- [ ] foundry-zksync must be able to verify smart contracts

# 3. Using cast as your bash scripting framework should not be used for production
- [ ] foundry-zksync contract creation must first work for `create`, `create2`, `createAccount`, and `create2Account`

# 4. Using any library or tooling from the era-contracts/zksync-contracts repo should not be used for production
- [ ] the current [zksync-contracts](https://www.npmjs.com/package/@matterlabs/zksync-contracts) npm packages is currently recommended in the zkSync documentation, however it's very unclear what code it is using and how to contribute. At the moment, this lack of clarity could be considered a security issue. In the future, the [era-contracts](https://github.com/matter-labs/era-contracts) should replace it

# 5. Using 5.0.0+ of openzeppelin libraries and hardhat 
- [ ] Many hardhat libraries are hard-pegged to specific versions of openzeppelin libraries, typically 4.0.0. It's very unclear what the impact of these hard-coded dependencies are