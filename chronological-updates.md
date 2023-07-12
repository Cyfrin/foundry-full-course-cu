# Lesson 0

# Lesson 1

# Lesson 2

# Lesson 3

# Lesson 4

# Lesson 5

# Lesson 6

1. `forge test -m` has [been replaced](https://github.com/foundry-rs/foundry/blob/98a1862d7e9f6ee53ef7371c683b10f2322ffa23/CHANGELOG.md?plain=1#L30) by `forge test --mt`
2. If you have trouble installing anvil, you can install it with this command:
```
# install Anvil
cargo install --path ./anvil --profile local --force
```
Per the [foundry docs](https://book.getfoundry.sh/getting-started/installation#building-from-source)

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

# Lesson 12

In the latest version of openzeppelin/openzeppelin-contracts `ERC20Mock.sol` file has been updated with **0** constructor parameters.
You should use `forge install openzeppelin/openzeppelin-contracts@v4.8.3 --no-commit` command to download the appropriate version synced with the video.

# Lesson 13

# Lesson 14

# Lesson 15


