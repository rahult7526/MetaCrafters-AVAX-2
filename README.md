Project Title

Function Frontend

Description

This solidity code is the solution to the assessment of the "ETH PROOF: Intermediate ETH + AVAX Course" by Metacrafters. 
The requirements of the assessment are: For this project, create a simple contract with 2-3 functions. Then show the values of those functions in front-end of the application.
Solution Overview
The solution consists of two main components:

Smart Contract: The Assessment.sol file contains the smart contract written in Solidity. It implements a basic bank contract with functionalities for depositing, withdrawing, and transferring funds. It emits three events: Deposit, Withdraw, and Transfer.
JavaScript Code: The index.js file demonstrates how to capture and handle the emitted events. It connects to the Ethereum network, attaches the deployed contract, and sets up event listeners for the three events. When an event is triggered, relevant information is logged to the console.
Getting Started
Executing Program
Follow these steps to set up and run the solution:

Clone the repository to your local machine.
Install the project dependencies by running the following command in the terminal: npm install
Deploy the smart contract to a local Ethereum network. You can use tools like Hardhat or Ganache for local development and testing. Make sure to update the network provider URL and contract address in the index.js file.
Use npx hardhat node to setup hardhat environment.
npx hardhat run --network localhost scripts/deploy.js to deploy in the localhost.
Authors
Contributors' names and contact info

Ankit Kunwar @rahult7526
