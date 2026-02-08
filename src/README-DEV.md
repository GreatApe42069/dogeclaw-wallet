# Development Notes for DogeClaw Wallet

## SPV Node Setup
- The `BlockchainService.java` file contains the core SPV logic.
- DNS seed connectivity, peer handshaking, block syncing, and mempool monitoring will be implemented in this class.
- Doginals support requires handling metadata and token minting on-chain.

## Project Structure
```
dogeclaw-wallet/
│
├── src/
│   ├── BlockchainService.java  # Core SPV logic (header/blockchain sync, transactions)
│   ├── README-DEV.md           # Development notes
│
├── README.md                   # Project Overview
├── CHANGELOG.md                # Progress tracking