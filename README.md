# 🖼️ NFT-Verse – Full Stack NFT Marketplace

**NFT-Verse** is a decentralized NFT marketplace built using **Next.js**, **Hardhat**, and **Solidity**. It allows users to mint, buy, and sell NFTs on the Ethereum blockchain with seamless wallet integration.

---

## 🚀 Features

- 🔐 Wallet integration (MetaMask)
- 🎨 NFT minting
- 💸 Buy/Sell NFTs on the marketplace
- 🧠 Smart contracts with Hardhat
- 🧑‍💻 React + Next.js frontend
- 🎯 Fully decentralized and Web3-ready

---

## 🧱 Tech Stack

| Layer          | Technology      |
|----------------|-----------------|
| Smart Contracts| Solidity, Hardhat |
| Frontend       | Next.js, React   |
| Blockchain     | Ethereum (via MetaMask) |
| Styling        | CSS / Tailwind (assumed) |
| Web3           | ethers.js or web3.js (TBD) |

---

## 🗂 Project Structure

NFT-Verse/
│
  ├── client/ # Frontend (Next.js app)
│ ├── public/ # Images and assets
│ ├── src/app/ # Pages, layout, styles
│ ├── package.json
│
  ├── contracts/ # Solidity smart contracts (if present)
  ├── hardhat.config.js # Hardhat configuration
  ├── package.json # Project-level dependencies


---

## 🛠 Installation & Setup

### 📦 Prerequisites

- Node.js (v16+ recommended)
- MetaMask browser extension
- Hardhat installed globally or via npm
- Ethereum testnet account (e.g., Goerli)

---

### 🔧 Install Dependencies

In both root and client directories:

```bash
# Root project
npm install

# Frontend
cd client
npm install

```
### Start Frontend

cd client
npm run dev

### Compile & Deploy Smart Contracts

npx hardhat compile
npx hardhat run scripts/deploy.js --network <your-network>

### Wallet Setup

Open MetaMask
Connect to your testnet (e.g., Goerli)
Add test ETH via a faucet

