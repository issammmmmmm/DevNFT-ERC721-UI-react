# 🖼️ DevNFT Interface – Day 4

This React app connects to a deployed ERC-721 smart contract and displays an NFT using `tokenURI()` data.

## 🧩 Features

- Connect wallet via MetaMask
- Read `tokenURI(tokenId)`
- Fetch and display NFT name, description & image

## 🧪 Smart Contract

- 📍 Contract Address: `0x39B6173A738526bcF8a801d0eE182e7d1a350dA5` 
- 🧠 Network: Sepolia 
- 🔗 [View on Etherscan](https://sepolia.etherscan.io/address/0x39B6173A738526bcF8a801d0eE182e7d1a350dA5)

## 🖼 Screenshots

### 🔌 Wallet connected
![connected](./screenshots/video.mp4)

### 🖼 NFT displayed
![nft_displayed](./screenshots/nft_displayed.png)

## 🧠 Metadata

Here’s the JSON used as `tokenURI`:

```json
{
  "name": "DevNFT #1",
  "description": "This is my first NFT with metadata + image",
  "image": "https://ipfs.io/ipfs/bafybeigka47qnjsi3w5nqzeuwkbszyw35jusjludneohsbo7zbrf7u2z6a"
}
