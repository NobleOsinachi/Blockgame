
Blockgame
=========

This repository contains my implementation of the Blockgames tasks by Zuri and Nest coin. It includes a staking dApp and a simple token creation contract.

Staking dApp
------------

The `StakingDapp` folder contains a decentralized application for staking tokens. Users can stake their tokens and earn rewards based on the amount of time their tokens are locked. The application is built using Solidity and JavaScript.

### Installation

1.  Clone the repository: `git clone https://github.com/Hexdee/Blockgame.git`
2.  Navigate to the `StakingDapp` folder: `cd StakingDapp`
3.  Install dependencies: `npm install`
4.  Compile the smart contracts: `npx hardhat compile`
5.  Deploy the contracts to a local network: `npx hardhat node` followed by `npx hardhat run --network localhost scripts/deploy.js`
6.  Start the application: `npm start`

### Usage

Once the application is running, users can connect their wallet and stake their tokens. They can also view their staking history and claim their rewards.

Token creation contract
-----------------------

The `Tokens` folder contains a simple contract for creating ERC-20 tokens. The contract is built using Solidity.

### Installation

1.  Clone the repository: `git clone https://github.com/Hexdee/Blockgame.git`
2.  Navigate to the `Tokens` folder: `cd Tokens`
3.  Install dependencies: `npm install`
4.  Compile the smart contracts: `npx hardhat compile`
5.  Deploy the contract to a local network: `npx hardhat node` followed by `npx hardhat run --network localhost scripts/deploy.js`

### Usage

Once the contract is deployed, users can interact with it to create their own tokens. They can set the name, symbol, and total supply of the token.

Conclusion
----------

This repository serves as a demonstration of my skills in developing decentralized applications and smart contracts using Solidity and JavaScript. Feel free to use the code as a reference or as a starting point for your own projects.

1 / 1
