# 🗳️ Decentralized Voting System

A full-stack decentralized application (dApp) that allows users to vote for candidates securely on the blockchain. Built with **Solidity**, **Hardhat**, and **React**.

## 🚀 Features
- **Smart Contract:** Secure voting logic written in Solidity.
- **Blockchain Backend:** Local Ethereum network powered by Hardhat.
- **Modern UI:** Glassmorphism dashboard built with React and Vite.
- **Wallet Integration:** Connects with MetaMask for on-chain transactions.

## 🛠️ Tech Stack
- **Frontend:** React.js, Ethers.js, Vite
- **Blockchain:** Solidity, Hardhat, Hardhat Ignition
- **Wallet:** MetaMask

## 🏁 Getting Started

### 1. Clone the repository
```bash

cd blockchain
npm install
npx hardhat node
In a second terminal, deploy the contract:

Bash
npx hardhat ignition deploy ./ignition/modules/Voting.js --network localhostSet up the Frontend
Copy the deployed contract address into frontend/src/constants.js.

Bash
cd ../frontend
npm install
npm run dev
