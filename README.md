# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
GAS_REPORT=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

## Dependencies

```shell
npm install ethers hardhat @nomiclabs/hardhat-waffle \
ethereum-waffle chai @nomiclabs/hardhat-ethers \
web3modal @walletconnect/web3-provider \
easymde react-markdown react-simplemde-editor \
ipfs-http-client @emotion/css @openzeppelin/contracts
```

## Overview of Dependencies

- hardhat - Ethereum development environment
- web3modal - An easy-to-use library that allows users to connect their wallets to your app
- react-markdown and simplemde - Markdown editor and markdown renderer for the CMS
- @emotion/css - A great CSS in JS library
- @openzeppelin/contracts - Open source implementations of useful smart contract standards and functionality