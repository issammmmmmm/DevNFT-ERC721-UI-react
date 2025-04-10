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

- 🔗 tokenURI: [https://gateway.pinata.cloud/ipfs/bafkreigkh7l2pn6p4op6bpweb6b7guy7sxg37idanyagn5avuh2zbmulsy)

## 🖼 Screenshots

look through the files

## 🧠 Metadata

Here’s the JSON used as `tokenURI`:

```json
{
  "name": "DevNFT #1",
  "description": "This is my first NFT with metadata + image",
  "image": "https://ipfs.io/ipfs/bafybeigka47qnjsi3w5nqzeuwkbszyw35jusjludneohsbo7zbrf7u2z6a"
}
