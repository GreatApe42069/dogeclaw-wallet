# DogeClaw Wallet

## 🚀 Overview
DogeClaw Wallet is a self-reliant and autonomous cryptocurrency wallet for **Dogecoin**, **Doginals**, **Dunes**, and **DRC-20** tokens. Built as a seamless SPV (Simplified Payment Verification) wallet, it performs autonomous DNS seed connections, peer handshakes, block sync, transaction parsing, and mempool monitoring, ensuring constant functionality and readiness for operations. This wallet integrates directly into the OpenClaw architecture, allowing agents to perform onchain cryptocurrency operations autonomously using the `/dogeclaw` skill.

---

## 🔑 Features
- **Fully Autonomous Dogecoin Wallet**:
  - Automatically connects to DNS seeds and peers.
  - Syncs blockchain headers and blocks to stay updated.
  - Parses transactions and monitors the mempool in the background.
  - Fetches current wallet balance.
  - Send & receive Dogecoin seamlessly with transaction broadcasting.

- **Ecosystem Token and NFT Operations**:
  - Support for Dogecoin ecosystem tokens Doginals, Dunes, and DRC-20.
  - Deploy and mint DRC-20 tokens.
  - Deploy and mint Dunes tokens.
  - Mint Doginals NFTs and handle metadata.

- **Agent Integration**:
  - Accessible via a `/dogeclaw` skill in OpenClaw.
  - API integration for balance checking, token handling & transactions for agents.

---

## 🛠️ Setup & Requirements
1. **Prerequisites**:
   - Redis server installation and configuration for session memory.
   - Existing SPV components (using BitcoinJ for Dogecoin).
   - WSL2 Linux environment for running the SPV node as a service.

2. **To Install**:
```bash
git clone https://github.com/GreatApe42069/dogeclaw-wallet.git
cd dogeclaw-wallet
npm install # Install necessary dependencies (if any for testing).
```

3. **To Start**:
   - Ensure that the Dogecoin SPV node is configured as a service to run on boot.
   - Use the built-in DogeClaw commands or APIs to interact.

---

## ⚖️ License
The DogeClaw Wallet is an open-source project licensed under the GNU Public License (GPLv3).