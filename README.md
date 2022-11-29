# Joint Savings Accounts Using Smart Contracts

This program was written for a fintech startup company who operates its own cross-border, Ethereum-compatible blockchain that connects different financial institutions. The program automates creation of joint savings accounts using Solidity smart contracts with two user addresses.
The smart contract uses Ether management functions to implement financial institution requirements for providing the features of a joint savings account.
The features include depositing and withdrawing funds.

---

## Technologies

This application is compatible with Solidity. Specifically, we're running it in version 5.0 for maximum compatibility.

To run the program, use an Ethereum IDE. We decided to use Ethereum IDE "Remix" which is browser based.

This program will work on Windows, MacOS and Linux with a Safari, Firefox or Chrome browser.

Documentation for Solidity can be found [here.](https://docs.soliditylang.org/en/v0.8.17/)

Documentation for Remix - Ethereum IDE can be found[here.](https://remix-ide.readthedocs.io/en/latest/index.html)


---

## Installation Guide

Open a compatible web browser.

Navigate to ``` https://remix.ethereum.org/```

Click the File Explorer icon and upload the "joint_savings.sol" file.

---

## Usage

Once the file "joint_savings.sol" is open, navigate to the Solidity Compiler. Choose compiler version 0.5.0 and click "Compile joint_savings.sol".

The file has now been compiled and is ready be deployed.

Navigate to the "Deploy & Run Transactions" window. For the purposes of our demo we are using a virtual enviroment. Choose "Remix VM (London)".

The program will populate with a handful of accounts each with 100 virtual ETH in them.

Choose one, enter your gas limit and click "Deploy". You should see a new Deployed Contract below named "JOINTSAVINGS AT 0X..." with 0X... being the new contract address.

You are now able to interact with the contract and using the accounts, transfer ETH between them all.
