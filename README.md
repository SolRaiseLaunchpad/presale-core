# SOLRAISE - Your Prime IDO Launchpad on Solana

SolRaise is the go-to platform for launching and participating in IDOs on the blazing fast Solana blockchain. Empowering projects to raise capital and investors to discover the next big thing, SolRaise provides a seamless and secure environment for token launches. Join us in shaping the future of decentralized finance (DeFi) with SolRaise.

We've published our smart contract that is designed for facilitating the sale of SPL tokens with additional features, including a presale mechanism and allocation tickets. The contract is built using the Anchor framework.

Website: https://solraise.xyz

Twitter: @SolRaisePad

Telegram: @SolRaise_Launchpad

## Solana Token Sale Contract Key Features

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
   git clone https://github.com/albywok/spl-vending-machine.git
   cd spl-vending-machine
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


© 2024 SolRaise
