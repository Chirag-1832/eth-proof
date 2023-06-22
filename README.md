
# eth-proof



## My Token
A simple Solidity smart contract for managing a custom token.
## Requirements
The contract has public variables that store the details about the coin:

Token_name: Token name (string)

Token_abb: Token abbreviation (string)


Total_supply: Total supply of the token (uint)
The contract has a mapping of addresses to balances:

map: Mapping of addresses to token balances (address => uint)
The contract has a mint function:

Parameters: address _a - the address to mint tokens to, uint _x - the amount of tokens to mint
Increases the total supply by _x
Increases the balance of the _a address by _x
The contract has a burn function:

Parameters: 

address _a - the address to burn tokens from, 

uint _x - the amount of tokens to burn

Checks if the balance of the _a address is greater than or equal to _x

Decreases the total supply by _x

Decreases the balance of the _a address by _x
## Usage
Deploy the MyToken contract to a Remix IDE or any solidity supporting enviornment.

Interact with the contract using the following functions:

mint: Mint new tokens to an address.

Parameters: address _a - the address to mint tokens to, uint _x - the amount of tokens to mint.

Example: mint(address _a, uint _x)

burn: Burn existing tokens from an address.

Parameters: address _a - the address to burn tokens from, uint _x - the amount of tokens to burn.

Example: burn(address _a, uint _x)

Note: The contract assumes that the deployer has the necessary permissions to mint and burn tokens.


## Authors

- Chirag Arora



## License

This code is licensed under the MIT License. See the LICENSE file for details.

