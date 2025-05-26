# MarketX
# 🛒 Digital Marketplace Smart Contract

This Solidity smart contract allows users to **list and purchase digital items** using an **ERC20 token** (e.g., USDC). It is ideal for selling digital assets like eBooks, music, art, or software with metadata stored on IPFS or other decentralized storage.

---

## 📦 Features

- 🔐 Owner-only deployment
- 📤 List items with name, metadata URI, and price
- 💰 Purchase items using ERC20 tokens (configurable)
- 🔍 Track purchases and access metadata
- ✅ Emits events for listings and sales

---

## 🛠️ Tech Stack

- Solidity ^0.8.0
- OpenZeppelin Contracts (ERC20 & Ownable)
- IPFS-compatible metadata URIs
- Ethereum or any EVM-compatible chain

---

## 🧠 Smart Contract Overview

### Constructor

```solidity
constructor(address _tokenAddress)
