# Polygon Boilerplate Smart Contract

This project demonstrates a basic smart contract using Hardhat, deploying to the Polygon Mumbai Testnet.

### Install

```
npm install
```

### ENV

Make sure to create a `.env` file

You will need to create an app [on Alchemy](https://dashboard.alchemyapi.io/) and save your `ALCHEMY_API_URL` to your to your `.env` file

You will also need to save your `PRIVATE_KEY` exported from Metamask to your `.env` file as well

### Compile

```shell
npx hardhat compile
```

### Deploy

```shell
npx hardhat run scripts/run.js --network matic
```

### JS App

You can now use the contract address and the JSON ABI in a JS app, for example, this is how I am interacting with the smart contract:

- https://polygon-boilerplate.vercel.app/

- https://github.com/SeanPlusPlus/polygon-boilerplate

### Inspiration

This code was inspired by an excellent [https://buildspace.so/solidity](Solidity tutorial on Buildspace).
