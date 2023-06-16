# Final Solidity Project 


This is an illustration of a basic cryptocurrency contract written in the Solidity programming language. It enables the creation and destruction of tokens, and provides real-time tracking of their circulation and value. All the terms and conditions of the contract are described here

## Description

The Coin Contract is a smart contract written in Solidity that facilitates the creation and destruction of tokens. It maintains a record of token ownership and circulation. The contract includes public variables to store token-specific information such as the Token Name, Token Abbreviation, and Total Supply. Token ownership can be traced using a mapping of addresses to balances.

The contract features a mint function, which increases the token supply and assigns the same amount to the balance of the "sender" address. On the other hand, the burn function reduces the overall token supply and deducts tokens from the balance of the "sender" address. The burn function incorporates conditionals to ensure that the "sender" address has a positive balance equal to or greater than the amount being burned.

The contract has a mint function that adds an amount to the supply and sends the same amount to the "sender" address's balance. By contrast, the burn function decreases the overall supply and deducts tokens from the "sender" address's holdings. Conditionals are built into the burn function to guarantee that the "sender" address has a positive balance greater than or equal to the amount being burnt.

## Introduction

### Setting Up

To utilize the Coin Contract, follow these steps:

1. Obtain the contract's code from the Solidity file.
2. Modify the contract as needed, including revising the Token Name, Token Abbreviation, and Total Supply.
3. Compile the Solidity code using a Solidity compiler or development environment of your choice.
4. Utilize a tool like Remix to deploy the compiled contract on the Ethereum network of your choosing.

## Putting code to work

Once the contract is deployed, it can be accessed and interacted with using the provided methods:

Tokens can be created using the mint function by specifying the recipient's address and the desired value (number of tokens).
Tokens can also be destroyed by utilizing the burn function, which requires the owner's address and the value of the tokens (in tokens) as inputs. This function deducts the specified amount from the available token supply and decreases the remaining balance of the "sender" address by the same amount.

## Help

If you have any problems or queries when working with Solidity, see the relevant documentation for your compiler or development environment. Support from online Solidity developer groups or forums is also available.

Number of Contributors

1. Izaac Manuelle Lachica - Mapua University

### License 

The Izaac Manuelle Lachica License governs use of this work. 
