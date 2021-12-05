A Simple wallet contract to deposit and withdraw ETH.

### Dependencies
- Truffle
- OpenZeppelin

### Install Dependencies
`npm install`

### Compile Contract
`truffle compile`


### Deploy Contract (Rinkeby testnet)

- Add a `.env` file with the following variable:
```
INFURA_ID=<your infura rinkeby project id>
MNEMONIC=<your metamask memonic phrase>
ETHERSCAN_API_KEY=<your etherscan project id>
```

- deploy contract 
`truffle migrate --network rinkeby` 



### Verify contract (Rinkeby testnet)
`truffle run verify Wallet --network rinkeby`



An instance of this contract is deployed here
https://rinkeby.etherscan.io/address/0xaC78B0FAfb928d9F1007f8aE3446Ea2C86F61C20#code

