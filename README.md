# SolidityBeginner

This is an example of a simple cryptocurrency contract in the Solidity programming language. Tokens (or coins) may be issued and destroyed, and their circulation and value can be tracked in real time. All terms and conditions of the contract are detailed here.

# Description
The Coin Contract is a Solidity smart contract that facilitates the minting and burning of tokens. It keeps track of token holdings and circulation. The contract has built-in public variables for storing token-specific information such the Token Name, Token Abbreviation, and Total Supply. Token ownership may be tracked by a mapping of addresses to balances.

The contract has a mint function that adds an amount to the supply and sends the same amount to the "sender" address's balance. By contrast, the burn function decreases the overall supply and deducts tokens from the "sender" address's holdings. Conditionals are built into the burn function to guarantee that the "sender" address has a positive balance greater than or equal to the amount being burnt.

# Introduction
Setting Up
Here's how to utilize the Coin Contract:

Step one: get the contract's code from the Solidity file. 2. Make the necessary changes to the contract, such as revising the Token Name, Token Abbreviation, and Total Supply. 3 Use a Solidity compiler or development environment of your choosing to compile the Solidity code. 4 Use a tool which is Remix to release the built contract on the Ethereum network of your choosing.

# Putting code to work
Once the contract has been deployed, it may be accessed and interacted with using the supplied methods:

Tokens may be created with the mint function by providing the address where they should be sent and the required value (number of tokens). The second method for eradicating tokens is to use the burn function, where the token's owner's address and the token's value (in tokens) are entered as inputs. The function will take the given amount out of the available supply and lower the "sender" address' remaining balance by the same amount.

# Help
If you have any problems or queries when working with Solidity, see the relevant documentation for your compiler or development environment. Support from online Solidity developer groups or forums is also available.

# Number of Contributors

Izaac Lachica - Mapua University
# License
The Izaac Lachica License governs use of this work.
