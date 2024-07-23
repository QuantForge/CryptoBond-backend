# CryptoBond Backend

Welcome to the **CryptoBond Backend**! This repository contains the backend components for the CryptoBond decentralized crypto gambling platform. The backend is responsible for deploying and interacting with smart contracts on the Tron blockchain.

## Technologies Used

- **TronBox:** Development framework for deploying smart contracts on Tron.
- **TronWeb:** JavaScript library for interacting with Tron blockchain.
- **Node.js:** JavaScript runtime for backend development.
- **Solidity:** Programming language for writing smart contracts.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org) (version 14 or higher)
- [TronBox](https://github.com/tronprotocol/tronbox) (install via npm)
- [TronWeb](https://github.com/tronprotocol/tronweb) (install via npm)
- TronLink wallet for interacting with the Tron blockchain.

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/QuantForge/cryptobond-backend.git
   cd cryptobond-backend

2. **Install dependencies:**
   ```sh
   npm install

3. **Configure TronBox:**
   ```javascript
	const tronWeb = new TronWeb({
		fullHost: 'https://api.trongrid.io',
		privateKey: 'YOUR_PRIVATE_KEY',
	});

	const contractAddress = 'YOUR_CONTRACT_ADDRESS';

4. **Deploy the smart contract:**
   ```sh
   tronbox migrate --network development

- **For mainnet deployment:**
   ```sh
  tronbox migrate --network mainnet


5. **Start the development server:**
   ```sh
   npm start

6. **Open:**
   ```sh
   http://localhost:3000

### Usage


1. **Connect Wallet:**
   ```sh
  - Users connect their Tron wallet (e.g., TronLink) to the CryptoBond platform.

2. **Place Bets:**
   ```sh
   - Users can place bets through the user interface, which interacts with the smart contracts on the Tron blockchain.

3. **View Results:**
   ```sh
  - Users can see the outcome of their bets and their updated balance.

### Contributing


We welcome contributions to CryptoBond! To contribute:

   ```sh
   Fork the repository.

   ```sh
   Create a new branch for your feature or bug fix.

   ```sh
   Make your changes and test thoroughly.

   ```sh
   Submit a pull request with a clear description of your changes.

### Contact

**For questions or support, reach us at :**

	- [Email](quantforg@gmail.com)
	- [GitHub](https://github.com/QuantForge)

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---------------

Thank you for using CryptoBond! We hope you enjoy your experience and have fun betting! 🚀