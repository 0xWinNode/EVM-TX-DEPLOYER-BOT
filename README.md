# EVM TX & DEPLOYER BOT
The Evm Testnet Bot is a powerful tool designed for interacting with EVM-compatible networks. This bot automates transaction processes, enabling users to perform actions such as ETH to WETH swap interactions seamlessly and daily. Additionally, it provides a built-in smart contract deployment feature, making it an ideal solution for you to do your testnet airdrop.

## Table Of Contents
- [EVM TX \& DEPLOYER BOT](#evm-tx--deployer-bot)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [NOTE](#note)
  - [CONTRIBUTE](#contribute)
  - [SUPPORT](#support)

## Prerequisite
- Git
- Node JS (v22)                       

## BOT FEATURE
- Multi Account 
- Support PK & SEED
- Auto TX Daily (Wrap Unwrap ETH)
- Deploy Smart Contract


## Setup & Configure BOT

### Linux
1. Clone project repo
   ```
   git clone https://github.com/0xWinNode/EVM-TX-DEPLOYER-BOT.git && cd EVM-TX-DEPLOYER-BOT
   ```
2. Run
   ```
   npm install
   ```
3. Run
   ```
   cp -r accounts/accounts_tmp.js accounts/accounts.js && cp -r config/config_tmp.js config/config.js
   ```
4. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
5. Configure the bot config
    ```
   nano config/config.js
    ```
6. To run Auto TX
   ```
   npm run start
   ```
7. To run Contract Deployer
    ```
    npm run deploy
    ```
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone
   https://github.com/0xWinNode/EVM-TX-DEPLOYER-BOT.git
   ```
   and cd to project dir
   ```
   cd EVM-TX-DEPLOYER-BOT
   ```
3. Run 
   ```
   npm install
   ```
5. Navigate to `evm-tx-deployer-bot` directory. 
6. Navigate to `accounts` folder and rename `accounts_tmp.js` to `accounts.js`.
7. Now open `acccounts.js` and setup your accounts. 
8. Now Back to `evm-tx-deployer-bot` directory and Navigate to `config` and rename `config_tmp.js` to `config.js` adjust the `config.js` as needed.
9.  Back to `evm-tx-deployer-bot` directory.
10. To start the app open your `Command Prompt` or `Power Shell`
11. To run auto Tx Bot
    ```
    npm run start
    ```
12. To run Smart Contract Deployer
    ```
    npm run deploy
    ```

## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
2. start the bot


## NOTE
DWYOR

## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks.

## SUPPORT

want to support me for creating another bot ?
**star** my repo or buy me a coffee on

EVM : `0xa7816292d470BC4e4426a5FAdA71A42C0f370C53`

SOLANA : `95m5zAspEMNy5Dhc6hGCuUKygP8e7kLLC6dz23cJ13nk`
