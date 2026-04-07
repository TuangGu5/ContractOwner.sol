# ContractOwner.sol
ContractOwner.sol7
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract ContractOwner {
    address public owner;

    constructor() {
        owner = msg.sender;
    }
}
Add contract templates for learning
Improve contract modularity
Clean code formatting
