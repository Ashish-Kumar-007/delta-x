# Delta-X Rewards

Delta-X Rewards is a decentralized rewards system that grants users Delta-X tokens based on their wallet transactions. By registering their wallet address on our platform, users become eligible to earn Delta-X tokens for every transaction they make.

## Problem Solved

### Encouraging Wallet Usage

One of the challenges in the decentralized finance (DeFi) ecosystem is incentivizing users to engage more frequently with their wallets. Often, users may not be motivated to make transactions unless there's a clear benefit. Delta-X Rewards solves this problem by offering a tangible incentive: a 10% reward in Delta-X tokens for every transaction made from a registered wallet.

By promoting the registration of wallet addresses on our platform, we encourage users to interact with their wallets more often. This not only benefits the user by allowing them to accumulate rewards, but it also helps increase overall activity within the DeFi space.

### Future Utility of Delta-X Tokens

As the Delta-X ecosystem grows, users will have the opportunity to use their earned tokens across various DeFi platforms. Whether it’s staking, lending, or providing liquidity, the Delta-X tokens earned through transactions will have real value and utility in the broader DeFi ecosystem. This creates a compelling reason for users to register their wallet addresses and participate in the program, knowing that their rewards will have future benefits.

## Features

- **Automatic Token Rewards**: Earn 10% of the transaction amount in Delta-X tokens for every transaction made from your registered wallet.
- **Cross-Chain Tracking**: We use Chainlink's CCIP (Cross-Chain Interoperability Protocol) to monitor and reward cross-chain transactions.
- **Real-Time Monitoring**: Wallet activity is tracked through Alchemy's WebSocket Service (WSS) for real-time updates and token distribution.

## How It Works

1. **Register Your Wallet**: Users must first register their wallet address on our website.
2. **Track Transactions**: Once registered, the wallet is tracked using Alchemy's WSS. All transactions, including cross-chain transactions, are monitored.
3. **Earn Delta-X Tokens**: For every transaction, 10% of the transaction amount is automatically awarded to the wallet in the form of Delta-X tokens.

## Future Implementation

Due to some urgent work, the full implementation of the features described above has been delayed. However, the following features are planned for future updates:

- **Integration of Chainlink CCIP**: The cross-chain tracking feature will be implemented to ensure that transactions made on different blockchains are properly rewarded with Delta-X tokens.
- **Automated Token Distribution**: The smart contract responsible for awarding Delta-X tokens will be finalized and deployed, allowing for seamless and automatic reward distribution.
- **Enhanced User Interface**: A more user-friendly interface will be developed for wallet registration and transaction tracking.

Stay tuned for updates, as these features will be rolled out in the coming weeks. Your patience and understanding are appreciated as we work to deliver the best possible experience.

## Getting Started

### Prerequisites

- **Metamask Wallet**: Users must have a Metamask wallet to register and receive Delta-X tokens.
- **Optimism Testnet Network**: Ensure your wallet is connected to the Optimism testnet network.

## Technical Overview

### Smart Contract

- The Delta-X token is an ERC-20 token deployed on the Ethereum network.
- The smart contract is responsible for issuing rewards based on the transaction data received from Alchemy and Chainlink.

### Alchemy WebSocket Service

- Alchemy WSS is used to subscribe to real-time updates for registered wallet addresses.
- The service listens for transactions and triggers the reward mechanism whenever a transaction is detected.

### Chainlink CCIP

- Chainlink's Cross-Chain Interoperability Protocol (CCIP) is used to check and validate cross-chain transactions.
- This ensures that users are rewarded for transactions made across different blockchains.

## Contributing

We welcome contributions from the community. Please feel free to open issues, submit pull requests, or suggest improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
