# nft-ipfs

![image](https://github.com/bradylee123/nft-ipfs/blob/main/images/screen.png)

This application mints images into NFTs on the Ethereum blockchain, upload images to IPFS and display the images on the screen.

### DEMO - https://dazzling-khorana-ba5f95.netlify.app/

- Connect to the site in Metamask via the Ropsten test network
- Only admin is able to mint NFTs on the site


### Initialize application

Install dependencies:
```sh
npm install
```

Create a .env file in root:
```sh
INFURA_API_KEY='YOUR_INFURA_API_KEY'
PRIVATE_KEY='YOUR_PRIVATE_KEY'
```

### Deploy to Ropsten & Test smart contract & Run

To deploy:
```sh
truffle migrate --reset --network ropsten
```

To test smart contract:
```sh
truffle test
```

To run:
```sh
npm start
```

## Minting an NFT

![image](https://github.com/bradylee123/nft-ipfs/blob/main/images/mint.png)

## Image uploaded to IPFS

![image](https://github.com/bradylee123/nft-ipfs/blob/main/images/ipfs.png)