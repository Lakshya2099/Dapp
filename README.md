This project is a decentralized application (dApp) built with a focus on blockchain and real-time client-server communication. The app leverages Solidity for smart contracts, Hardhat for testing and deployment, and React for the frontend, with Socket.io to handle real-time interactions.

## Technology Stack & Tools

- **Solidity** - Smart Contract Development & Testing
- **JavaScript** - Core language for Frontend and Testing
- **Hardhat** - Development Framework for Ethereum
- **Ethers.js** - Blockchain Interaction Library
- **React.js** - Frontend Framework
- **Socket.io** - Real-time Client & Server Communication

## Requirements for Initial Setup

Ensure you have **Node.js** installed on your machine. You can download it [here](https://nodejs.org/).

## Setting Up

Follow these steps to set up and run the project locally:

### 1. Clone or Download the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Tests

```bash
npx hardhat test
```

### 4. Start Hardhat Node

This command will start a local Ethereum blockchain instance for testing.

```bash
npx hardhat node
```

### 5. Run Deployment Script

In a new terminal window, deploy the smart contracts to the local Hardhat network:

```bash
npx hardhat run ./scripts/deploy.js --network localhost
```

### 6. Start Socket.io Server

In a separate terminal window, start the Socket.io server:

```bash
node server.js
```

### 7. Start Frontend

In another terminal, start the React frontend:

```bash
npm run start
```

## Project Structure

- **contracts/** - Solidity smart contracts
- **scripts/** - Deployment and other scripts
- **server.js** - Socket.io server configuration
- **src/** - React frontend codebase

## Contributing

Feel free to fork the repository and make pull requests. For significant changes, please open an issue first to discuss your idea.
