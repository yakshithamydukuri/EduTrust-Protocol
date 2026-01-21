# EduTrust Protocol: Blockchain University Certificate Verification

EduTrust is a decentralized application (dApp) built on the Ethereum blockchain (Sepolia Testnet) that allows universities to issue digital diplomas as NFTs (ERC-721 tokens). This system ensures that academic credentials are immutable, tamper-proof, and instantly verifiable by employers without third-party intervention.

---

## 🚀 Live Demo

You can run this project by simply opening the index.html file in any modern browser with the MetaMask extension installed.

---

## 🛠 Features

- **University Portal (Admin):** Restricted to the contract owner. Allows the university to mint unique NFT certificates by providing the student's wallet address and the IPFS metadata URI.
- **Public Verification:** Anyone can enter a Certificate Token ID to verify the holder's identity and view the original document via IPFS.
- **Enforced Protocols:** Ensures all metadata follows the ipfs:// standard.
- **Glassmorphism UI:** A premium, high-fidelity interface built with React and Tailwind CSS.

---

## 🧠 Technical Architecture

- **Smart Contract:** Written in Solidity using OpenZeppelin's ERC721URIStorage.
- **Frontend:** Single-file React application using Tailwind CSS for styling.
- **Blockchain Interaction:** Ethers.js (v6) for connecting to the Sepolia network.
- **Decentralized Storage:** IPFS (InterPlanetary File System) for hosting certificate images/PDFs and metadata.

---

## 📜 Smart Contract Details

- **Network:** Ethereum Sepolia Testnet  
- **Contract Address:** 0xC5D08640e195B79AFd088618bD4437E4446f98F7  
- **Standard:** ERC-721 (Non-Fungible Token)

---

## 📦 Installation & Setup

1. Clone the repository:
git clone https://github.com/yakshithamydukuri/edutrust-protocol.git

2. Open index.html in your browser.

3. Ensure MetaMask is installed and switched to the Sepolia Test Network.

---

## 🛡 License

This project is licensed under the **MIT License**.  

You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the project, provided that the original copyright notice and this permission notice are included in all copies or substantial portions of the software.

See the LICENSE file for more details.
