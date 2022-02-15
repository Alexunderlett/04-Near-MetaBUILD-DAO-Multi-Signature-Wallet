## Documentation on how to run the project

## Dependencies

- Linux or Mac
- node ≥ 16

## Installing

```bash
git clone https://github.com/RainbowDAO/03-Hackathon-DAO-multi-signature-wallet.git
cd 03-Hackathon-DAO-multi-signature-wallet
```

Install truffle by running the command:
```bash
npm install -g truffle
```

**Note**: Only the Metamask wallet is available for this demo


## Deploy Contracts
Open a local node or complete the information in the ```truffle-config.js``` and add the mnemonic to the ```secret```

```bash
npm install -g @truffle/hdwallet-provider
truffle compile && truffle migrate
```
You will deploy contracts
- Creator

### Creator
Create multi-signature wallet, manage multi-signature wallet address, store basic information

### MultiSign
The specific logic of multiple wallets


