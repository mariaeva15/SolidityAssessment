# Solidity Assessment

Introduction
The "MyToken" Solidity program showcases fundamental features for creating and overseeing tokens on the Ethereum blockchain. It serves as a straightforward token contract, demonstrating capabilities like token creation, minting, burning, and essential data storage such as name, abbreviation, and overall supply.

Description
This contract embodies essential functionalities, allowing the initiation of new tokens, minting of additional tokens, and the controlled burning of existing tokens. Crucial token information, including name, abbreviation, and overall supply, is made publicly available. The contract is designed to ensure that the burning function only proceeds when the sender possesses an adequate balance.

Getting Started
Running the Program
Go to the Remix website by visiting Remix Ethereum IDE.

Create a New File:

Click on the "+" icon in the left-hand sidebar to create a new file.
Save the file with a .sol extension (e.g., MyToken.sol).
Copy and Paste Code:

Copy the Solidity code from this repository's MyToken.sol file.
Paste the code into the newly created file in Remix.
Compile the Code:

Click on the "Solidity Compiler" tab in the left-hand sidebar.
Ensure the "Compiler" option is set to "0.8.18" (or another compatible version).
Click on the "Compile MyToken.sol" button.
Deploy the Contract:

Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
Select the "MyToken" contract from the dropdown menu.
Click on the "Deploy" button.
Interact with the Contract:

Once the contract is deployed, you can interact with it by using the provided functions.
Explore and execute the available functions, such as minting and burning tokens.
Enjoy the Program:

Experience the functionalities of the contract and observe its behavior.

To use this contract, you can follow the instructions below:

Minting Tokens
Call the mint function, providing the recipient's address and the number of tokens to mint.
Burning Tokens
Call the burn function, providing the sender's address and the number of tokens to burn. The function will check if the sender's balance is sufficient before burning.
Authors
Maria Evangelicalyn Ong

License
This project is licensed under the MIT License. See the LICENSE.md file for details.

License Information
This contract is licensed under the MIT License. SPDX-License-Identifier: MIT.

Solidity Code Explanation
The Solidity contract MyToken implements the following features:

Public Variables:

tokenName: Stores the name of the token.
tokenAbbrv: Stores the abbreviation of the token.
totalSupply: Tracks the total supply of the token.
Mappings:

balances: Maps addresses to their respective token balances.
Mint Function:

mint(address _address, uint _value): Mints a specified amount of tokens and assigns them to the specified address, updating the total supply and the recipient's balance.
Burn Function:

burn(address _address, uint _value): Burns a specified amount of tokens from the sender's address, updating the total supply and the sender's balance, but only if the sender has enough tokens to burn.
Requirements
The contract includes public variables to store token details.
Utilizes a mapping to manage balances for each address.
Implements a mint function to increase the total supply and update a recipient's balance.
Implements a burn function to decrease the total supply and update the sender's balance, ensuring the sender has sufficient tokens.
