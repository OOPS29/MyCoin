
# MyCoin Smart Contract

MyCoin is a basic ERC20-like smart contract that allows for the creation and destruction of tokens. It includes functionalities for minting new tokens to an address and burning tokens from an address, while managing the total supply of the token.

## Requirements

1.Solidity version 0.8.18 or later.

2.An Ethereum development environment such as Remix, Truffle, or Hardhat.
## Contract Details

1.Token Name: MyCoin

2.Token Abbreviation: MC

3.Total Supply: Initially set to 0 and updated as tokens are minted or burned.

## Deployment

Deploy the 'MyCoin' contract using your 'Remix' Ethereum development environment.

## Usage/Examples

// Mint 1000 tokens to the address 0xAbC...
myCoin.mint(0xAbC123456789, 1000);

// Burn 500 tokens from the address 0xAbC...
myCoin.burn(0xAbC123456789, 500);

## Authors

- [OOPS29] (https://github.com/OOPS29)

## License
This project is licensed under the MIT License.








