# Create a token

This Solidity program is a simple "Hello World" program that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to get a feel for how it works.
This Solidity program is a simple "MyToken" program that demonstrates the basic syntax and functionality like minting and burning of Token of the Solidity programming language. The purpose of this program is to serve as an introduction to solidity and token mechanism on Ethereum blockchain.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a single function that returns the string "Hello World!". This program serves as a simple and straightforward introduction to Solidity programming, and can be used as a stepping stone for more complex projects in the future.

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a token named METACRAFTERS abbreviated as MTC. This program allows to mint , burn, and have the information about total supply and the balance of addressess of token. 
This program will serve as the gate to understanding and moving onto complex projects in solidity.
## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:

javascript
pragma solidity ^0.8.4;

contract HelloWorld {
    function sayHello() public pure returns (string memory) {
        return "Hello World!";
    }
}



To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "HelloWorld" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "HelloWorld" contract in the left-hand sidebar, and then click on the "sayHello" function. Finally, click on the "transact" button to execute the function and retrieve the "Hello World!" message.
use REmix - an online Solidity IDE , to execute the program
steps:
1) Create a New File: click on the"+" available on the left slidebar of the page and save the file with a .sol extension.
2) Paste the code given in meta [https://github.com/encoded2203/meta2/tree/main]
3) Compile the code: click on the "Solidity Compiler" tab in the left-hand sidebar and ensure e the "Compiler" option is set to "0.8.9" and then click on the "Compile MyToken.sol" button.
4) Deploy and Contract: Click on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.
5) Interact with the Contract:Once the contract is deployed, we can call mint and burn function by using address. Then click on the "transact" button to execute the function and retrieve the updated information.

## Authors
Neha Kumari Nandini
nehakumarinandini@gmail.com


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
