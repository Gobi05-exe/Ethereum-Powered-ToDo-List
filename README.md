
# Ethereum Powered To-Do List

This project implements a decentralized To-Do List application powered by Ethereum Smart Contracts. It leverages the Solidity language for writing smart contracts, the Truffle framework for development and deployment, and a basic web interface for interacting with the blockchain.

## Features
- Fully decentralized To-Do list managed on the Ethereum blockchain
- Smart contract written in Solidity
- Local development using Truffle and Ganache
- Basic web frontend to interact with the contract
- Includes unit tests for contract functionality

## Technologies Used
- Solidity
- Truffle Framework
- Ganache (for local blockchain simulation)
- Web3.js
- HTML, JavaScript

## Project Structure
```
.
├── build/                  # Compiled contract artifacts
├── contracts/              # Solidity smart contracts
│   ├── Migrations.sol
│   └── TodoList.sol
├── migrations/             # Truffle migration scripts
├── src/                    # Frontend source files
│   ├── index.html
│   └── app.js
├── test/                   # Test scripts for contracts
├── truffle-config.js       # Truffle configuration
├── package.json            # Project dependencies
├── bs-config.json          # BrowserSync configuration
└── .gitignore
```

## Prerequisites
- [Node.js](https://nodejs.org/)
- [Truffle](https://trufflesuite.com/truffle/)
- [Ganache](https://trufflesuite.com/ganache/)
- [MetaMask](https://metamask.io/) (for browser-based Ethereum wallet)

## Getting Started

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Run Local Blockchain**
   Start Ganache to simulate a local Ethereum network.

3. **Compile & Deploy Smart Contracts**
   ```bash
   truffle compile
   truffle migrate
   ```

4. **Run the Frontend**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:3000` (or specified port).

5. **Interact with the Application**
   Connect MetaMask to your local Ganache network and test the To-Do List functionality.

## Testing
Run the included smart contract tests:
```bash
truffle test
```

## License
This project is licensed under the Apache 2.0 License.

## Notes
- Ensure Ganache is running before deploying the contracts.
- MetaMask must be configured to point to the same network as Ganache.
- For production deployment, additional security and network considerations apply.
