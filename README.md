# Push Donut Project

A testnet dApp built on Push Chain's Donut Testnet using the Push SDK. It demonstrates universal contract deployment with Hardhat and integrates the UniversalCounter smart contract. The project highlights smooth transaction execution, SDK integration, and serves as a learning tool for Push-based development.

## Push Donut Testnet App

A sample dApp built on the Push Chain Donut Testnet, showcasing universal app deployment using Push Protocol’s SDK and tooling.

## Features

- Deploys on Push Chain’s Donut Testnet (Chain ID: 42101)
- Integrated with Push SDK for smooth smart contract interaction
- Uses `UniversalCounter.sol` smart contract example
- Built with Hardhat for smart contract development
- Supports on-chain event triggering and frontend integration

## Stack

- Solidity + Hardhat
- Push SDK
- EVM compatible networks
- Push Donut Explorer

## How to Run Locally

```bash
git clone https://github.com/your-username/push-donut-project.git
cd push-donut-project
npm install
npx hardhat run scripts/deploy.js --network pushDonutTestnet
Note
This is an early build for testing and learning purposes.
Ideal for developers experimenting with universal app deployment on Push Chain.
