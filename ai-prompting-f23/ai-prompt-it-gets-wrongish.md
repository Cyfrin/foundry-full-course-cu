The following is my solidity code:

```solidity
// SPDX-License-Identifier: MIT

pragma solidity 0.8.18;

contract AINotHelpful {
    uint256 public myNumberOne;

    function assemblyStore(uint256 newNumber) external {
        assembly {
            sstore(0x00, newNumber)
        }
    }

    function assemblyView() external view returns (uint256) {
        assembly {
            mstore(0, result)
            return(0, 0x20)
        }
    }
}
```

When I deploy the contract and run `assemblyView` I get 0 no matter what I call `assemblyStore` with. How can I fix my code so that my `assemblyView` function returns the value of `myNumberOne`?