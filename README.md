# Enlighten
Enlighten is an open library on IPFS

### Features
- All users can add books to the library
- All users can get books from the library
- All books are uploaded to IPFS and minted as NFT 

### How to run locally
- Deploy smart contract by following the instructions in this
# Books

This smart contract stores all books uploaded to Enlighten and also mint them as NFTs

### secret.json
Provide your API keys and private key in given below
{
    "APP_ID": "Your https://rpc.maticvigil.com API key",
    "PRIVATE_KEY": "Your private key",
    "POLYGONSCAN_API_KEY": "Your polygonscan.com apikey"
}

### Compile smart contract

```bash
npx hardhat compile
```

### Deploy smart contract

This would deploy the smart and display the contract address

```bash
npx hardhat run scripts/deploy.js
```

### Verify contract
Be sure to replace `YOUR_CONTRACT_ADDRESS` with the contract address you got after deploying the Smart Contract

```bash
npx hardhat verify `YOUR_CONTRACT_ADDRESS`
```
- Open `book.js` and provide your API keys and private key in the first 3 lines
- Update smart contract address

### View
Open `index.html` in your browser
