SplitPayment Web3 Application
This repository contains a web3 application that utilizes the SplitPayment smart contract to send split payments to multiple addresses.

Description
The application consists of an index.js file responsible for interacting with the Ethereum network via Web3.js and a smart contract SplitPayment.sol that enables sending split payments.

The index.html file is the entry point of the application. It provides a simple user interface to input recipient addresses and corresponding amounts for split payments.

index.js
The index.js file initializes Web3, connects to the SplitPayment smart contract, and defines the logic for sending split payments.

SplitPayment.sol
The SplitPayment smart contract, written in Solidity, provides the functionality to send split payments to multiple addresses. Only the owner of the contract can initiate transactions.

Prerequisites
Before running the application, ensure you have Node.js and npm installed on your system. You'll also need a local Ethereum network such as Ganache or a connection to a public Ethereum network like Infura.
