# Token Price Monitor

This repository contains code for retrieving token prices on the Ethereum blockchain.

## Instructions

1. **Clone Repository**: Clone this repository to your local machine.
 ```bash
git clone <repo_link>
```

3. **Install Dependencies**: Run the following command to install the necessary dependencies:
   ```bash
   npm install
4. **Update .env File**: Before running the application, make sure to update the .env file with your configuration details.
5. **Run Application**: Execute the following command to run the application:
   ```bash
   node index.js
   ```
### Add Custom Token
1. **Add Token Details**: in index.js file.
```bash
   await checkPair({
      inputTokenSymbol: 'ETH',
      inputTokenAddress: '0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee',
      outputTokenSymbol: 'MKR',
      outputTokenAddress: '0x9f8f72aa9304c8b593d555f12ef6589cc3a579a2',
      inputAmount: web3.utils.toWei('1', 'ETHER')
    })

   await checkPair({
         inputTokenSymbol: 'ETH',
         inputTokenAddress: '0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee',
         outputTokenSymbol: 'USDT',
         outputTokenAddress: 'USDT_CONTRACT_ADDRESS',
         inputAmount: web3.utils.toWei('1', 'ETHER')
       })
```
