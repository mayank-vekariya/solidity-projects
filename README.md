# Lottery: Smart Contract

## Overview
This project implements a simple lottery system using a Solidity smart contract. The contract allows players to participate by sending 1 ether, and once there are at least 3 players, the manager can pick a random winner who receives the entire balance.

## Contract Details
- **Manager**: The person who deploys the contract and has special permissions, such as viewing the contract's balance and picking a winner.
- **Players**: Participants who send 1 ether to the contract to enter the lottery.
- **Winner**: The randomly selected player who wins the total ether in the contract.

## How to Use
1. **Deploy the Contract**: The contract should be deployed on the Ethereum network by the manager.
2. **Participate**: Any user can participate in the lottery by sending exactly 1 ether to the contract using the `participate()` function.
3. **Check Balance**: The manager can check the total balance of the contract using the `getBalance()` function.
4. **Pick Winner**: Once there are at least 3 participants, the manager can call the `pickWinner()` function to randomly select a winner who receives the total ether in the contract.

## Technologies Used
- **Solidity**: Smart contract programming language used to implement the lottery logic.
- **Remix IDE**: For developing and deploying the smart contract.
- **Ethereum Network**: The platform where the smart contract is deployed and executed.
