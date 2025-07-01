# 🧪 Neon-Solana Native Swap Demo

This project demonstrates deploying a modified PancakeSwap-style DEX on the [Neon EVM Devnet](https://neonlabs.org), integrated with Solana SPL tokens using ERC20ForSPL.

---

## 📡 Deployment Details

```bash
npm run deploy
✅ Deployment Summary (Network: curvestand)
Deployer address: 0x35c47BB4706654bE1B0D42be4c6B969aBc187fDb

Airdropped: 8451 NEON

Deployer balance: 1548.239064522208610994 NEON

🏗️ Contracts Deployed
Contract	Address
WNEON	0x0387013189a71211Ea20627CE4d38b3aa67274A3
PancakeFactory	0xD3eaF75e84d3E9e34Ac6D4353812bfe0FE9686ce
PancakeRouter	0xEE1F9048985CF8b0642A606F09F8A5d373D320D1
ERC20ForSPLMintable (Token A)	0x48C4BDf659C5F705224Ae19385Ae0f8Dd7b87FE0
ERC20ForSPLMintable (Token B)	0x05B52F4B3fF5e9AD29Ecd80f8a83a4944F03E899

🪙 SPL Token Details
Token A
EVM Address: 0x48C4BDf659C5F705224Ae19385Ae0f8Dd7b87FE0

SPL Address: DBGW27Yaf4Kp89jepMGKfPr7GfAWhmAK6asFjBCgV5C1

Name: Token A

Symbol: TOKEN_A

Decimals: 9

Mint Authority: 0x35c47BB4706654bE1B0D42be4c6B969aBc187fDb

Token B
EVM Address: 0x05B52F4B3fF5e9AD29Ecd80f8a83a4944F03E899

SPL Address: 9wCWRzuLeae9fwPaAMtaZEYSWj52nBG67rLSzUV9QkaZ

Name: Token B

Symbol: TOKEN_B

Decimals: 12

Mint Authority: 0x35c47BB4706654bE1B0D42be4c6B969aBc187fDb

🛠️ Setup & Usage
Install dependencies and run deployment:

bash
Copy
Edit
npm install
npm run deploy
Ensure your .env or Hardhat config contains correct RPC and private key for the curvestand Neon test network.
