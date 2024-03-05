# ERC20 and Vault Contracts

This repository contains the implementation of ERC20 token and Vault contracts.

## ERC20 Contract

The ERC20 contract is a standard implementation of the Ethereum token standard. It allows for the creation and management of tokens adhering to the ERC20 specification. This contract provides functionalities such as transferring tokens between addresses, approving addresses to spend tokens on behalf of another address, and querying the balance of a specific address.

### Features
- Transfer tokens between addresses.
- Approve spending allowance for a specific address.
- Check token balance of an address.

## Vault Contract

The Vault contract provides a secure and convenient way to store tokens. It allows users to deposit ERC20 tokens into the vault, withdraw tokens from the vault, and check their token balance within the vault. The vault ensures the safety of deposited tokens by implementing proper access control and security measures.

### Features
- Deposit tokens into the vault.
- Withdraw tokens from the vault.
- Check token balance within the vault.

## Usage

### ERC20 Contract
1. Deploy the ERC20 contract to the Ethereum blockchain.
2. Utilize the contract functions to transfer tokens, approve spending allowances, and query token balances.

### Vault Contract
1. Deploy the Vault contract to the Ethereum blockchain.
2. Interface with the vault contract to deposit tokens, withdraw tokens, and check token balances within the vault.

## Development

The contracts are written in Solidity, a smart contract language for Ethereum. They can be compiled and deployed using tools like Truffle or Remix.

## License

This project is licensed under the [MIT License](LICENSE).

