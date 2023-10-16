# Chronological Updates

For those who prefer the video format here we have a video with a recopilation of this updates you can follow along:

[![Chronological Updates](https://img.youtube.com/vi/G_evB-LLkRU/0.jpg)](https://www.youtube.com/watch?v=G_evB-LLkRU)

# Lesson 0

# Lesson 1

# Lesson 2

# Lesson 3

# Lesson 4

## Lesson 4 Challenge

We are not going to spoil you the solution of most the challenges but when is our fault we have to aknowledge it. In this challenge we made a little mistake on the smart contract, in line 40 there is a typo stating `10e10` instead of `1e10` which is the correct value. This is the reason why the challenge is not working as expected.

```solidity
function solveChallenge(uint256 priceGuess, string memory yourTwitterHandle) external {
        uint256 actualPrice = getPrice();
        if (getDecimals() == 8) {
            actualPrice = actualPrice * 10e10; // <======== HERE!
        }
        if (actualPrice + 3e18 > priceGuess && actualPrice - 3e18 < priceGuess) {
            _updateAndRewardSolver(yourTwitterHandle);
        } else {
            revert LessonFour__WrongPrice();
        }
    }
```

So if you use the price feed as normal with 18 decimals and your price feed returns a value like:

```
1572890000000000000000
```

You will need to add one zero to the end of the number to make it work:

```
15728900000000000000000
```

# Lesson 5

# Lesson 6

1. `forge test -m` has [been replaced](https://github.com/foundry-rs/foundry/blob/98a1862d7e9f6ee53ef7371c683b10f2322ffa23/CHANGELOG.md?plain=1#L30) by `forge test --mt`
2. If you have trouble installing anvil, you can install it with this command:

```
# install Anvil
cargo install --path ./anvil --profile local --force
```

Per the [foundry docs](https://book.getfoundry.sh/getting-started/installation#building-from-source)

3. The exntension used on the video is [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml) which has being deprecated, so please use [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml) instead.

# Lesson 7

1. `forge test -m` has [been replaced](https://github.com/foundry-rs/foundry/blob/98a1862d7e9f6ee53ef7371c683b10f2322ffa23/CHANGELOG.md?plain=1#L30) by `forge test --mt`
2. To run the [foundry-devops](https://github.com/Cyfrin/foundry-devops/) tool, you might need to install [jq](https://stackoverflow.com/questions/37668134/how-to-install-jq-on-mac-on-the-command-line)

# Lesson 8

# Lesson 9

The modulo examples shown on remix in the demo are the wrong way around.

It shows on screen (line 11):

```
// 2 % 2 = 0. 2 % 3 = 1.      2 % 6 = 0.  2 % 7 = 1
```

What it should be:

```
// 2 % 2 = 0. 3 % 2 = 1.      6 % 2 = 0.  7 % 2 = 1
```

# Lesson 10

# Lesson 11

On the latest version of Openzeppelin the `_isApprovedOrOwner` and `_exists` are no longer included on [OpenZeppelin ERC721](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/IERC721.sol) so we have two options:

1. Use the exact same version of OpenZeppelin as the one used on the video: `forge install openzeppelin/openzeppelin-contracts@v4.8.0 --no-commit`.

2. Replace the functions for their equivalent on the latest version of OpenZeppelin:

   - for `_isApprovedOrOwner` replace it for: `_isAuthorized`.
   - `_isAuthorized(_ownerOf(tokenId), msg.sender, tokenId)` is equivalent to `_isApprovedOrOwner(msg.sender, tokenId)`.

# Lesson 12

In the latest version of openzeppelin/openzeppelin-contracts `ERC20Mock.sol` file has been updated with **0** constructor parameters.
You should use `forge install openzeppelin/openzeppelin-contracts@v4.8.3 --no-commit` command to download the appropriate version synced with the video.

# Lesson 13

# Lesson 14

# Lesson 15
