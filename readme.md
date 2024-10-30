# Decentralized Escrow Application

Welcome to the Decentralized Escrow Application, a project developed as part of the [Alchemy University](https://university.alchemy.com) Week 5 final exercise. This application allows users to deploy and manage escrow smart contracts on the blockchain.

## Overview

This DApp enables the deployer and arbiter to create escrow smart contracts by specifying a beneficiary. Only the arbiter has the authority to approve the contract, allowing the beneficiary to withdraw the funds. The project includes:

- Smart contract code and tests
- A React-based frontend application
- A backend server for persistent data retrieval

## Project Structure

1. **Frontend** - `/app`
2. **Backend** - `/server`
3. **Escrow Contract** - `/contracts/Escrow.sol`
4. **Contract Tests** - `/tests`

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Hardhat](https://hardhat.org/)

### Installation

1. **Clone the repository:**

   git clone <repository-url>
   cd DecentralizedEscrowApp

2. **Install dependencies:**
   - For Hardhat: `npm install`
   - For Frontend: `cd app && npm install`
   - For Backend: `cd server && npm install`

## Usage

### Hardhat

- **Compile Contracts:**
  - With Hardhat: `npx hardhat compile`
  - With npm scripts: `npm run compile`
  - Artifacts will be generated in `/app/src/artifacts`.

- **Test Contracts:**
  - With Hardhat: `npx hardhat test`
  - With npm scripts: `npm run test`

- **Start Local Node:**
  - With Hardhat: `npx hardhat node`
  - With npm scripts: `npm run node`

### Frontend

- **Start Development Server:** `npm start`
  - At the root level, it runs the npm script `start` which runs `cd app && npm start`.
  - You can also `cd app` and run `npm start`.
  - Access the application at `http://localhost:3000`.

### Backend

- **Start Express Server:** `npm run server`
  - At the root level, it runs the npm script `server` which runs `cd server && npm run dev`.
  - You can also `cd server` and run `npm run dev`.
  - The server provides persistent data access for deployed contracts.

## License 

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for details.