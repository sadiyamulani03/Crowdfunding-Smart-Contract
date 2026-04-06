# 💰 Crowdfunding Smart Contract (Solidity)

This is my first Web3 project built using Solidity,It is a simple crowdfunding smart contract deployed using Remix.

## &#x20;

## 🚀 Features

* Users can contribute ETH to a campaign
* Tracks total funds raised
* Stores contributor list
* Goal-based funding system
* Owner can withdraw funds only if:

  * Deadline has passed
  * Funding goal is reached
* Refund system if:

  * Goal is NOT met
  * Deadline has passed

## 🧠 Smart Contract Logic

* `deposit()` → Allows users to fund the campaign
* `isGoalMet()` → Checks if funding goal is achieved
* `withdrawFunds()` → Allows owner to withdraw funds
* `refund()` → Allows contributors to claim refund if goal is not met
* `getContributorCount()` → Returns number of contributors

  

## 🛠 Tech Stack

* Solidity (^0.8.0)
* Remix IDE
* Ethereum Virtual Machine (Remix VM)

## 📸 Screenshots

Deployed Contract:
<img width="1903" height="1016" alt="Screenshot 2026-04-04 154446" src="https://github.com/user-attachments/assets/bc99d663-cded-4bcd-8b52-483da5148f43" />

First Deposit Record:
<img width="1894" height="1008" alt="Screenshot 2026-04-04 155142" src="https://github.com/user-attachments/assets/31d021f1-5be5-4327-929a-b4d9550536c8" />


## 🔮 Future Scope

* Build frontend
* Deploy on testnet (Polygon / Sepolia)

## 🙌 Author

Built by Sadiya Mulani
