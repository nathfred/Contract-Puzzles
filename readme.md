# Contract Puzzles

A collection of smart contract "puzzles" focused on improving your ability to **read smart contracts**, understand their behavior, and write **clever tests** to exploit or interact with them — **without modifying the contracts themselves**.

## 🧩 What This Is

This project is part of a course exercise where each game contract contains a challenge:
Your goal is to write tests that successfully set isWon to true — without touching the contract's code.

## 🧠 Learning Objectives
Develop deeper smart contract intuition
Practice debugging with console.log
Learn how to use Hardhat tests for behavioral analysis
Simulate real-world contract interaction and potential attack surfaces

## 🛠 Tech Stack
1. Solidity
2. Hardhat
3. JavaScript (for testing)

## 🚀 Getting Started
Clone the repo:

```bash
git clone https://github.com/yourusername/contract-puzzles.git
cd contract-puzzles

Install dependencies:

npm install

Run all tests:

npx hardhat test
```

## 💡 Tip: Run specific game test files to speed up your workflow. For example:

npx hardhat test test/game1Test.js
Each contract has its own corresponding test file (e.g., Game1.sol ➝ game1Test.js).

## 📂 Project Structure

contracts/
  Game1.sol
  Game2.sol
  ...
test/
  game1Test.js
  game2Test.js
  ...

🪪 License
MIT

