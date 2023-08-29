# beezyCoin

beezyCoin is an ERC-20 token implemented as a smart contract on the Ethereum blockchain.

## Description

The beezyCoin contract has public variables that store the details about the token, such as its name, abbreviation, and total supply

. It also has a mapping of addresses to balances, which keeps track of how many tokens each address holds.

The contract includes a mint function that takes an address and a value as parameters. 

This function increases the total supply of tokens by the specified value and increases the balance of the specified address by that amount.

The contract also includes a burn function that works in the opposite way of the mint function. 

This function takes an address and a value as parameters and decreases the total supply of tokens by the specified value. 

It also decreases the balance of the specified address by that amount. 

The burn function includes a conditional statement to ensure that the balance of the specified address is greater than or equal to the amount being burned.

## Getting Started

## Installing

To install and use beezyCoin, you will need to have an Ethereum wallet that supports ERC-20 tokens. 

You can then interact with the beezyCoin contract on the Ethereum blockchain using your wallet.

## Executing

To execute functions on the beezyCoin contract, you will need to send transactions to the contract address from your Ethereum wallet.

You can use your wallet’s interface to specify which function you want to call and provide any necessary parameters.

## Authors

Beezy-cray

## License

This project is licensed under the MIT License
