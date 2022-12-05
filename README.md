# My NFT minter

This project demonstrates a basic deployment of a smart contract that mints NFTs on the Ethereum chain.

**Test locally**

```shell
REPORT_GAS=true npx hardhat test
npx hardhat run scripts/deploy.js --network goerli
```

**Deploy on testnet**
```shell
npx hardhat run scripts/deploy.js --network goerli
```

To see it on OpenSea

https://testnets.opensea.io/assets/goerli/[address of the deployed contract]/[nft number]

For all nfts for the ccount
https://testnets.opensea.io/assets/goerli/[public addres of wallet]