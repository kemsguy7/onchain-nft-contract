# KemsguyNFT ONChain Contract

This is a simple NFT contract that stores on-chain NFT data including the artwork and metadata.

## Setup and Run Project

1. Clone the repository
2. Install dependencies: `npm install`
3. Create a `.env` file with your private key
4. Compile the contract: `npx hardhat compile`
5. Deploy the contract: `npx hardhat run scripts/deploy.ts --network base_sepolia`
6. Verify the contract: `npx hardhat verify --network base_sepolia <contract-address>`

## Deployed and Verified Address

- **Network**: Base Sepolia (ChainId: 84532)
- **Contract Address**: 0x13a51Ac0C60DC6a775589cB5dce8f852FFaCC74b
- **Block Explorer**: https://sepolia.basescan.org/address/0x13a51Ac0C60DC6a775589cB5dce8f852FFaCC74b#code
