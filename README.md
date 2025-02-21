# Crypto-Savings-Vault 

## Project Description
Crypto Savings Vault is a simple Ethereum-based smart contract that allows users to deposit and withdraw ETH while keeping track of their balances.

## Smart Contract Address
`0x59452AdCB9d8fA6Ac9d43354bbEcB47E75E63551`

## Features
- Deposit ETH to save funds securely.
- Withdraw ETH anytime from your balance.
- Track your balance using the `getBalance` function.

## How to Use
### Deposit ETH
Send ETH to the contract using the `deposit` function:
```solidity
vault.deposit{value: amount}();
```

### Withdraw ETH
Call the `withdraw` function to retrieve your entire balance:
```solidity
vault.withdraw();
```

### Check Balance
Use the `getBalance` function to check your stored ETH balance:
```solidity
uint256 balance = vault.getBalance();
```

## License
This project is open-source and available under the MIT License.
