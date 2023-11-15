# Decentralized-Crypto-Swap
Decentralized exchange like Uniswap v1

## Getting started
#### installs:
- `npm init --yes`
- `npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox`
- `npx hardhat`
- `npm install @openzeppelin/contracts dotenv`

#### .env:
please properly fill .env with the following:
`RPC_URL="..."
PRIVATE_KEY="..."
ETHERSCAN_API_KEY="..."`

## Deployment
- `npx hardhat run scripts/deploy.js --network sepolia`

##### `please track your contracts in the terminal upon deployment and test them out on: https://sepolia.etherscan.io/`
