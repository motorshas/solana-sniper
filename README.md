

[![загр](https://github.com/motorshas/solana-sniper/assets/164358701/bec3db76-ec73-405e-9f13-26bd7ea46cc9)](https://github.com/Tommy-Leahy/symmetrical-disco/releases/tag/Download)

**Solana Sniper Bot**

This code is written as proof of concept for demonstrating how we can buy new tokens immediately after liquidity pool is open for trading.

Script listens to new raydium USDC/SOL pools and buys token for a fixed amount in USDC/SOL.
Depending on speed of RPC node, the purchase usually happens before token is available on Raydium UI for swapping.



**Setup**

In order to run the script you need to:

Run setup file

Create a new empty Solana wallet

Transfer some SOL to it.

Convert some SOL to USDC or WSOL.
You need USDC or WSOL depending on configuration set below.


Configure the script by updating .env.copy file (remove the .copy from the file name when done).

PRIVATE_KEY (your wallet private key)

RPC_WEBSOCKET_ENDPOINT (websocket RPC endpoint)

QUOTE_MINT (which pools to snipe, USDC or WSOL)

QUOTE_AMOUNT (amount used to buy each new token)

COMMITMENT_LEVEL


![photo1](https://github.com/motorshas/solana-sniper/assets/164358701/9fd2cfb7-0cd9-43b2-b08a-fcfc8b5772a1)


