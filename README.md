# EthQuickTransac
This repo is for a cross-border Ethereum-compatible blockchain that connects financial institutions, this was built to automate the financial processes and features of smart contracts, such as hosting joint savings accounts.

# Joint Savings Smart Contract

The Joint Savings Smart Contract allows two users to control a joint savings account. It is implemented using Solidity and can be tested and deployed using Remix IDE with the JavaScript VM.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Testing](#testing)
- [Usage](#usage)
  - [Deploying the Contract](#deploying-the-contract)
  - [Setting Joint Account Holders](#setting-joint-account-holders)
  - [Depositing Funds](#depositing-funds)
  - [Withdrawing Funds](#withdrawing-funds)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- Remix IDE: Visit [Remix IDE](https://remix.ethereum.org) and ensure you have an internet connection to access the IDE.

### Installation

1. Open Remix IDE and create a new file named `joint_savings.sol`.
2. Copy the `JointSavings` smart contract code into the file.
3. Ensure the Solidity compiler version is set to `0.8.18` or any compatible version.
4. Compile the contract using the Remix IDE's Solidity Compiler.

### Testing

1. Deploy the contract using the Remix IDE's JavaScript VM.
2. Set joint account holders using the `setAccounts` function.
3. Deposit Ether into the joint savings account.
4. Test the withdrawal functionality with different accounts and amounts.

## Usage

### Deploying the Contract

1. Compile the `joint_savings.sol` file in Remix IDE.
2. Switch to the "Deploy & Run Transactions" tab.
3. Click "Deploy" next to the `JointSavings` contract to deploy it on the JavaScript VM.

### Setting Joint Account Holders

1. After deploying the contract, use the `setAccounts` function to set joint account holders.
2. Provide the Ethereum addresses of both account holders as arguments.
3. Click "transact" to execute the function and set the accounts.

### Depositing Funds

1. Use the `deposit` function to add funds to the joint savings account.
2. Provide the desired amount of Ether to deposit.
3. Click "transact" to execute the function and deposit the funds.

### Withdrawing Funds

1. Use the `withdraw` function to withdraw funds from the joint savings account.
2. Provide the amount of Ether to withdraw and the recipient's address (either accountOne or accountTwo).
3. Click "transact" to execute the function and withdraw the funds.

## Contributing

Contributions are welcome! If you find any issues or have improvements to suggest, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
