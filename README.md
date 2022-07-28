# Solidity-Advanced
More Advanced Solidity contracts

### Goal

The goal of this exercise is to get practical skills in writing advanced smart contracts in Solidity, publishing, and testing contracts in the Remix IDE.

### Receiving Funds from the default contract function
Implement a Deposit contract with the following requirements:
- Stores the owner of the contract.
- People can deposit() ethers in the contract.
- People can read() the balance of the contract.
- Only the owner can transfer() the balance of the contract to other people.
  - Upon transferring five times, the contract self-destructs and transfers all the remaining contract balance to the owner.
  
Use modifiers where it is appropriate.

Add appropriate events for the functions.
