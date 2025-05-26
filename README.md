# 🛒 Digital Marketplace Smart Contract

This is a Solidity smart contract for a **Basic Digital Marketplace** that allows users to **list and purchase digital items** using an **ERC20 token** (e.g., USDC). Metadata for digital items can be stored on **IPFS** or similar decentralized storage.

---

## 📦 Features

- 👨‍💼 Owner-deployed contract
- 📤 List digital items with name, metadata URI, and token price
- 💳 Buy items using an ERC20 token
- 🔎 Access item metadata and track ownership
- 📈 Emits events for listing and purchases

---

## 🚀 Deployment Info

- **Network:** Ethereum Sepolia Testnet  
- **Deployed With:** Remix IDE  
- **Transaction Hash:**  
  `0xfcebadef0e62d7c3228b2a8118f4fac5595dd82d67ace54a78ebf05cd0f62fea`  
  [🔗 View on Etherscan](https://sepolia.etherscan.io/tx/0xfcebadef0e62d7c3228b2a8118f4fac5595dd82d67ace54a78ebf05cd0f62fea)

---

## 🧠 Contract Overview

### Constructor

```solidity
constructor(address _tokenAddress)
