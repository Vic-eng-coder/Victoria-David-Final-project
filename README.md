
# Web3 Farming DApp - README

Welcome to the Web3 Farming DApp project repository! This decentralized application (DApp) harnesses blockchain technology to create a farming platform on the Ethereum network. Users can engage in farming activities, earn rewards, and participate in yield farming.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Smart Contracts](#smart-contracts)
- [Testing](#testing)
- [Frontend](#frontend)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Web3 Farming DApp offers a user-friendly interface for Ethereum-based yield farming. This project emphasizes transparency and trust through the use of smart contracts. Users can participate in farming activities, stake assets, and earn rewards seamlessly.

## Features
- Explore available farming opportunities.
- Stake assets in farming pools to earn rewards.
- Automatic reinvestment: Reinvest earned rewards to compound yields.
- Real-time updates: Stay informed about your farming activities and rewards.
- Claiming rewards: Easily claim and withdraw your earned rewards.
- Ethereum Wallet Integration: Connect your Ethereum wallet (e.g., MetaMask) to participate directly.

## Getting Started
Follow these steps to set up the project locally and start participating in web3 farming.

### Prerequisites
- Node.js: Ensure Node.js is installed. Download it from nodejs.org.

### Installation
1. Clone the repository:
```bash
   git clone https://github.com/Vic-eng-coder/Victoria-David-Final-project.git 
```

2. Navigate to the project directory:

```bash
   cd Victoria-David-Final-project
```

3. Install required npm packages:

```bash
npm install
```


##  Usage
1. Start the development server:
    
 ```bash
    npm start
```
2. Open your web browser and navigate to http://localhost:3000 to access the DApp.

3. Connect your Ethereum wallet (e.g., MetaMask) to the DApp.

4. Explore farming opportunities, stake assets, and monitor your farming activity.

## Smart Contracts

   The smart contracts in this project facilitate the farming process. They handle staking, reward distribution, and reinvestment. These contracts are deployed on the Ethereum blockchain.

 -`FarmingFactory.sol`: Responsible for creating new farming opportunities.
 -`FarmingPool.sol`: Manages staking, reward distribution, and reinvestment for individual farming pools.

### Testing
Smart contract tests are located in the test folder. To run the tests:

Open a terminal in the project directory.
Run the following command to execute the tests:

```bash
truffle test
```
This command will initiate the smart contract tests and display the results in the terminal.


## Frontend

The DApp frontend is built using modern web technologies, including React.js. It provides an intuitive and interactive user interface for yield farming.

- **React.js**: Powers the DApp's user interface.
-**Web3.js**: The Ethereum JavaScript API for smart contract interaction.
-**MetaMask**: A popular Ethereum wallet browser extension for secure transactions.


## Contributing

Contributions to this project are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Make changes and test thoroughly.
4. Commit with clear and concise messages.
5. Push changes to your fork.
6. Submit a pull request describing your changes.


## License
This project is licensed under the MIT License.
