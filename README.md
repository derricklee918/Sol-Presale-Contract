# Solana-Presale-Smart-Contract

A smart contract designed to facilitate the sale of SPL tokens, featuring a presale mechanism and allocation tickets. It is built using the Anchor framework.

## Contact Me
Telegram: [@derricklee918](https://t.me/@derricklee918)


## Key Features

- **Token Sale:** The contract enables the sale of SPL tokens, allowing users to purchase tokens directly from the vending machine.
  
- **Presale Mechanism:** A configurable presale phase is implemented, allowing for exclusive token access for a specified duration before the public sale.

- **Allocation Tickets:** Users can acquire allocation tickets during the presale, providing them with reserved spots for purchasing SPL tokens.

- **Flexible Configuration:** The contract offers flexibility in configuring various parameters, such as presale and public sale start/end times, token prices, and ticket allocation limits.

## Prerequisites

Before you begin, make sure you have the following tools installed:

- [Rust](https://www.rust-lang.org/tools/install)
- [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)
- [Anchor CLI](https://project-serum.github.io/anchor/getting-started/installation.html)
- [Node.js](https://nodejs.org/en/download/)
- [Yarn](https://yarnpkg.com/getting-started/install)

## Getting Started

1. **Installation:** Clone the repository and install dependencies.

   ```bash
   git clone https://github.com/derricklee918/Sol-Presale-Contract.git
   cd Sol-Presale-Contract
   yarn
   ```

2. **Build the Smart Contract:**

   ```bash
   anchor build
   ```

3. **Run Tests:**

   ```bash
   anchor test
   ```

4. **Deploy:**

   Switch to your desired network and deploy
   ```bash
   anchor deploy
   ```

