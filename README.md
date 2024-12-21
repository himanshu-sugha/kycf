# KYC with Privacy (KYCF)

A decentralized KYC (Know Your Customer) system using ZK-SNARKs (Zero-Knowledge Succinct Non-Interactive Arguments of Knowledge). This project aims to verify KYC compliance without revealing sensitive information, ensuring privacy for users and compliance for organizations.

---

## Features

- **Zero-Knowledge Proofs**: Utilizes ZK-SNARKs for private and secure KYC verification.
- **Decentralized**: Built on Ethereum for transparency and immutability.
- **Privacy-Preserving**: Verifies compliance without exposing sensitive data.
- **User-Friendly Interface**: A React-based frontend for seamless interaction.
- **Smart Contracts**: Implements secure, on-chain functionality for KYC verification.

---

## Technology Stack

- **Frontend**: React, JavaScript, CSS
- **Backend**: Node.js (Express.js)
- **Blockchain**: Ethereum (Solidity, Truffle)
- **ZK-SNARKs**: Circom and SnarkJS
- **Local Blockchain**: Ganache

---

## Prerequisites

Ensure you have the following installed:

- **Node.js**: [Download Node.js](https://nodejs.org/)
- **Truffle**: Install globally with `npm install -g truffle`
- **Ganache**: [Download Ganache](https://trufflesuite.com/ganache/)
- **Metamask**: [Download Metamask](https://metamask.io/)

---

## Steps to Start

1. **Clone the Repository**:  
   Clone the project repository to your local machine and navigate into the project directory:  
   ```bash
   git clone https://github.com/himanshu-sugha/kycf.git
   cd kycf
   ```

2. **Install Dependencies**:  
   Install all the required dependencies by running the following command:  
   ```bash
   npm install
   ```

3. **Compile Smart Contracts**:  
   Use Truffle to compile the smart contracts for the project:  
   ```bash
   truffle compile
   ```

4. **Start a Local Blockchain**:  
   Open Ganache and start a local blockchain. Ensure the port matches the configuration in your Truffle settings.

5. **Deploy Smart Contracts**:  
   Deploy the compiled smart contracts to your local blockchain:  
   ```bash
   truffle migrate
   ```

6. **Run the Frontend Application**:  
   Navigate to the frontend folder and start the React application:  
   ```bash
   cd frontend
   npm run dev
   ```


---

