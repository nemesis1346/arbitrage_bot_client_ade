### Arbitrage Bot Client Ade Upwork with Ethereum

It was not an option anymore because we decided to go with solana, although this is working, the scripts are working

### node version
18

### Testing
 // Run the script
 ```
npx hardhat node  # in one terminal 
npx hardhat run --network localhost scripts/1_deploy_contracts.js # in another terminal for testing a liquidity pool
npx hardhat run --network localhost scripts/2_arbitrage.js # in another terminal for testing an arbitrage opportunity
 ```

### Warning
We decided to go with solana so better check the new repository arbitrage_bot_client_solana