# Baddosnei (BADD)

A clean, permissionless ERC20 token built for the African crypto community and DeFi builders.

![Solidity](https://img.shields.io/badge/Solidity-^0.8.19-blue)
![Foundry](https://img.shields.io/badge/Built%20with-Foundry-black)

## What is Baddosnei?

Baddosnei (BADD) is a simple, secure, and fully compliant ERC20 token designed as a starting point for DeFi experiments, community tokens, and educational purposes — especially for builders in Nigeria and across Africa.

It follows OpenZeppelin best practices and is completely permissionless after deployment.

## Contract Address: 0x1749abE3D2C382BDc0e230CD2aB2bF98cC19C4b7


Demo Transaction: View on Block Explorer https://testnet.iopn.tech/tx/0x83296188d8d85599303a3eec5cdb8286582e4f3aabc9cdc6536fe851e51edc45

## Features

- Standard ERC20 implementation
- 18 decimals
- Minted at deployment only
- No taxes, no blacklist, no owner functions after launch
- Fully decentralized and permissionless
- Verified on Etherscan (when deployed)

## Tokenomics

- Total Supply: 1,000,000 BADD
- Initial Distribution: 100% minted to deployer at launch
- Taxes: 0%
- Max Transaction: None
- Max Wallet: None

All tokens are available from day one — no vesting, no team allocation, fully fair launch.

## Deployment Instructions

### Prerequisites
- [Foundry](https://getfoundry.sh/) installed
- Private key with ETH for deployment

### Deploy on Testnet / Mainnet

```bash
# Clone the repo
git clone https://github.com/xofiglobalholdings-lang.git
cd xofiglobalholdings-lang

# Deploy using Foundry
forge script script/DeployTokenDaily.s.sol:DeployTokenDaily \
  --rpc-url $RPC_URL \
  --private-key $PRIVATE_KEY \
  --broadcast --verify