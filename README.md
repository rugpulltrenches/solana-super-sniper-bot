## Raydium Sniper Bot

#### Description:
The Raydium Sniper Bot aims to catch new pools on Raydium and execute buy/sell transactions to make a profit. It allows for manual and automated trading, giving users the flexibility to optimize their strategies and maximize returns.

https://youtu.be/JeY71PSXbgU

#### Features:
- **Wallet Registration**: Register your own wallet for transactions.
- **Track New Pools on Raydium**: Monitor new pools and filter them based on SOL amount. Filter feature can be disabled, and if disabled, catch all pools.
- **Buy and Sell**: 
  - Manual buy and sell for each pool which tracked.
  - Show the status of buy/sell on every pools.
  - Auto buy and sell with specific amount, time delay, profit, and loss percentages.
  - Jito Mode: Execute transactions with Jito mode, allowing manual adjustment of Jito fees.

## Getting Started

To use this Solana Bot Package, you will need to have a basic understanding of Solana, Raydium, and automated trading. Follow the instructions below to get started:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/lilmoat/solana-raydium-trading-bot
   ```
2. **Install Dependencies**:
   ```bash
   cd solana-raydium-trading-bot
   npm install
   ```
3. **Configure Your Wallet**: Update the configuration file with your wallet details and desired settings.

4. **Run the Bots**:
     ```bash
     npm run start
     ```

## Configuration Guide

### Frontend Configuration
Update the following environment variables in your frontend `.env` file:

- `VITE_SERVER_URL=`: Set this to your backend server URL.
- `VITE_RPC_URL=`: Define your RPC URL.
- `VITE_DEV_RPC_URL=`: Define your development RPC URL.
- `VITE_PINATA_API_KEY=`: Set your Pinata API key.
- `VITE_PINATA_URL=`: Set your Pinata URL.

### Backend Configuration
Update the following environment variables in your backend `.env` file:

- `MONGO_URL=`: Your MongoDB URL.
- `RPC_ENDPOINT=`: Define your RPC endpoint.
- `WEBSOCKET_ENDPOINT=`: Define your WebSocket endpoint.
- `RPC_SUB_ENDPOINT=`: Define your RPC subscription endpoint.
- `WEBSOCKET_SUB_ENDPOINT=`: Define your WebSocket subscription endpoint.
- `DEV_NET_RPC=`: Define your development network RPC.
- `DEV_NET_WSS=`: Define your development network WebSocket.
- `DEV_NET_SUB_RPC=`: Define your development network subscription RPC.
- `DEV_NET_SUB_WSS=`: Define your development network subscription WebSocket.
- `LOG_LEVEL=info`: Set the log level.
- `BLOCKENGINE_URL=`: Define your BlockEngine URL.
- `JITO_FEE=`: Set your Jito fee.
- `JITO_KEY=`: Set your Jito key.
- `CHECK_IF_MINT_IS_MUTABLE=`: Set this to true or false to check if mint is mutable.
- `CHECK_IF_MINT_IS_BURNED=`: Set this to true or false to check if mint is burned.
- `CHECK_IF_MINT_IS_FROZEN=`: Set this to true or false to check if mint is frozen.
- `CHECK_IF_MINT_IS_RENOUNCED=`: Set this to true or false to check if mint is renounced.
- `COMMITMENT_LEVEL=`: Set the commitment level.
- `ORIGIN_URL=`: The frontend URL for allowing CORS.

If you have any questions or want more customized app for specific use cases, please feel free to contact me to below contacts.

- Telegram: [@lilm0at](https://t.me/lilm0at)
