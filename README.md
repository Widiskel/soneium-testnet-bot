# Soneium Testnet BOT

## Table Of Contents
- [Soneium Testnet BOT](#soneium-testnet-bot)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [Soneium Incentive Testnet](#soneium-incentive-testnet)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [CONTRIBUTE](#contribute)
  - [SUPPORT](#support)

## Prerequisite
- Git
- Node JS
- Eth Sepolia Testnet (buy cheap on https://testnetbridge.com/sepolia by layer zero or you can find for free eth sepolia faucet)

## Soneium Incentive Testnet
New Airdrops : Soneium & Sonefi
Network : Sepolia & Soneium Minato Testnet

1. Bridge Sepolia 🔣Soneium : [HERE](https://bridge.soneium.org/en/testnet) (ensure bridge success and you have ETH on Soneium Minato Testnet, after that continue to the next step)
2. Open : https://testnet.sonefi.xyz/#/swap
3. Connect Wallet Testnet / New Wallet
4. Claim USDT.s faucet
5. Try to swap USDT.s to ETH (manually)
6. After done, go run the bot

## BOT FEATURE

- Multi Account 
- Support PK or Seed
- Auto Self Transfer (Transfer eth to your self)
- Auto Swap on Sonefi (Pair USDT.s > ETH)


## Setup & Configure BOT

### Linux
1. clone project repo
   ```
   git clone https://github.com/Widiskel/soneium-testnet-bot.git` and cd to project dir `cd soneium-testnet-bot
   ```
2. run
   ```
   npm install
   ```
3. run
   ```
   cp accounts/accounts_tmp.js accounts/account.js
   ```
5. configure your accounts
   ```
   nano accounts/account.js
   ```
6. configure the bot config
    ```
   nano config/config.js
    ```
7. to start the app run
    ```
    npm run start
    ```
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/Widiskel/soneium-testnet-bot.git
   ```
   and cd to project dir
   ```
   cd soneium-testnet-bot
   ```
4. Run 
   ```npm install```
6. Navigate to `soneium-testnet-bot` directory. 
7. Navigate to `accounts` folder and rename `accounts_tmp.js` to `accounts.js`.
8. Now open `acccounts.js` and setup your accounts. 
9. Now go back and Navigate to `config` and adjust the `config.js` as needed.
10. Back to `soneium-testnet-bot` directory. 
11.  To start the app open your `Command Prompt` or `Power Shell` again and run
    ```
    npm run start
    ```
    or
    ```
    node app/index.js
    ```

## Update Bot

To update bot follow this step :
1. run `git pull` or `git pull rebase` , if error run `git stash && git pull`
2. run `npm update`
3. start the bot

## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks. To get original unencrypted code just DM me on my social media original (index.js and src folder) are Obfuscated during build

## SUPPORT

want to support me for creating another bot ?
**star** my repo or buy me a coffee on

EVM : `0x0fd08d2d42ff086bf8c6d057d02d802bf217559a`

SOLANA : `3tE3Hs7P2wuRyVxyMD7JSf8JTAmEekdNsQWqAnayE1CN`
