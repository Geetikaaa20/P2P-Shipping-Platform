# P2P Shipping Platform

## Overview
A blockchain-based shipping platform that allows users to create shipping requests and carriers to accept and fulfill them using cryptocurrency.

## Features
- Shipping Request Creation
- Request Management
- Carrier Earnings Tracking
- Transparent Shipping Marketplace

## Smart Contract Functionality
- Create shipping requests with details and reward
- Accept shipping requests for specific periods
- Withdraw carrier earnings
- Request activation/deactivation

## Prerequisites
- Solidity ^0.8.0
- MetaMask or Web3-compatible wallet
- Web3.js library
- OpenZeppelin Contracts library

## Frontend Setup
1. Deploy the Solidity smart contract
2. Replace `contractAddress` with your deployed contract address
3. Update `contractABI` with your contract's ABI
4. Ensure Web3.js is properly linked

## Deployment Steps
1. Deploy smart contract on Ethereum network
2. Configure frontend with contract details
3. Connect MetaMask wallet
4. Start using the platform

## Key Contract Methods
- `createRequest()`: Users create shipping requests
- `acceptRequest()`: Carriers accept shipping requests
- `isAccepted()`: Check acceptance status
- `withdrawEarnings()`: Withdraw carrier earnings

## Security Considerations
- Fixed acceptance period
- Prevents duplicate acceptances
- Protects against reentrancy
- User-only request management

## Future Improvements
- Multi-tier rewards
- Dispute resolution mechanisms
- Carrier reputation system
- Advanced request filtering

## Technologies Used
- Solidity
- Web3.js
- HTML5
- CSS3
- JavaScript
- Ethereum Blockchain

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Push to the branch
5. Create a Pull Request

## License
MIT License

## Contact
[Your Contact Information]

