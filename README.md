# Hello-World-Solidity
You have to start somewhere! 
This is my very first (and very simple) smart contract: the classic **Hello World**.  
If you’re a beginner, feel free to use this lesson and share this experience with me. If you’re more experienced, I’d love your feedback to improve myself and my content!

## Contract
The contract `HelloWorld` contains:
- A private state variable `stateVariable` initialized with `"Hello World"`
- A public view function `GetHelloWorld()` that returns the message

## Repository structure
- Code → the Solidity contract
- README.md → project description & usage instructions
- Lesson's pdf : 1. Hello World.sol → A brief lesson on the basic concepts of Solidity to learn and an explanation of the Hello World code.

## What I learn 
Key concepts : 
- Solidity : a programming language for writing smart contracts on Ethereum.
- Smart contract : a program that runs automatically on the blockchain.
- License : Determines what others can do with your code. Always add at the top of the file // SPDX-License-Identifier: MIT
- Compiler version :A compiler translates Solidity code into bytecode for the Ethereum Virtual Machine (EVM). Since Solidity changes often, specifying the compiler version ensures compatibility.
- Visibility
    - public → accessible from inside and outside the contract.
    - private → accessible only inside the contract.
    - view → reads data without changing the blockchain.
    - pure → neither reads nor changes the blockchain.


