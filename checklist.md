# DogeClaw Wallet Progress Checklist

## Completed
1. **Core Wallet Functionality**: Verified existing SPV-based Dogecoin wallet framework.
   - Includes DNS seed connectivity, peer discovery, mempool monitoring.
   - Supports core functions: balance fetch, send/receive Dogecoin.
2. **Analysis Complete**:
   - Reviewed and understood SPV-related components (BlockchainService) for peer connections, blocks/headers download, and transaction parsing.
3. **SPV Auto-Initialization Plan**:
   - Designed startup mechanism for auto-launching wallet on system boot.


## To Do Next
### Core Functionality Enhancements
1. Add token management support:
   [ ] Deploy DRC-20 tokens.
   [ ] Mint DRC-20 tokens dynamically.
   [ ] Mint Dunes Tokens directly (including on-chain interactions).
   [ ] Handle Doginals NFT minting.
   
### Integration Tasks
[ ] Create `/dogeclaw` skill extension to interact with SPV wallet APIs.
[ ] Test seamless agent integration for DogeClaw Wallet functionalities.

### Automation and Deployment
[ ] Configure wallet service auto-start on WSL2 boot.
[ ] Test DNS seed connections, peer handshakes, and header/block sync on startup.

### Testing
[ ] Perform E2E (end-to-end) tests for all DogeClaw Wallet operations.
[ ] Validate block syncing, background transactions, mempool monitoring.
[ ] Test token deployments and mints.

---

Let’s track the progress directly in this file.