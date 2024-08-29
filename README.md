## Project Description

 This project is a Telegram bot designed for the TRON blockchain. The bot allows users to create a TRX wallet, check balances, transfer TRX, and swap tokens on SunSwap directly from Telegram.

## Requirements


* requests
* python-dotenv
* python-telegram-bot
* mnemonic
* aiosqlite
* httpcore[asyncio]
* tronpy

You can refer to your `requirements.txt` file for this.

## Installation

1. Clone the repository: `git clone https://github.com/adeel09/TronTelegramBot.git`
2. Create virtual env and install requirements.txt

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

3. Set up your environment variables: `cp .env.example .env` and fill in the necessary values

## Usage

Configure your telgram bot using BotFather.

Run `python3 main.py`  in project directory.

Go to you bot on telegram and send /start to get the usage instructions.
- Use /wallet to get your wallet address and private key.
- Use /balance to check your total balance in TRX.
- Use /tokenbalance <token_symbol>/<token_name> to check your balance of tokens.
- Use /transfer <receiver_address> <amount> to transfer tokens to another address.
- Use /swap <currency1> <currency2> <amount> to swap tokens. (inprogress/need fix)
- Use /getmemecoininfo <address> to get the info of the memecoins.
- Use /getwalletinfo <address> to get your wallet info.
- Use /getwallettransfers <address>  <token_address> to get an wallet address's tokens transfers.

## Contributing

If you'd like to contribute to this project, please submit a pull request with your changes. You can also report any issues you encounter.

Feel free to add or remove sections as necessary to fit your project's needs!
