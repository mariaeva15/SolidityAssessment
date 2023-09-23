# Solidity Assessment

## Introduction
The "MyToken" is a program showcases fundamental features for creating and overseeing tokens on the Ethereum blockchain. It serves as a straightforward token contract, demonstrating capabilities like token creation, minting, burning, and essential data storage such as name, abbreviation, and total supply.

## Description
This contract embodies essential functionalities, allowing the initiation of new tokens, minting of additional tokens, and the controlled burning of existing tokens. Crucial token information, including name, abbreviation, and total supply, is made publicly available. The contract is designed to ensure that the burning function only proceeds when the sender possesses an adequate balance.

## Getting Started
### Running the Program
Go to the Remix website at https://remix.ethereum.org/.

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

### To use this contract, you can follow the instructions below:

#### Minting Tokens
Call the mint function, providing the recipient's address and the number of tokens to mint.
#### Burning Tokens
Call the burn function, providing the sender's address and the number of tokens to burn. The function will check if the sender's balance is sufficient before burning.

### Authors
Maria Evangelicalyn Ong

### License
This project is licensed under the MIT License. See the LICENSE.md file for details.
