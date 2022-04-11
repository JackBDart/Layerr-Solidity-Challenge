# Layerr Smart Contract Challenge

## A) Challenge

### 1) Setup a project and create a contract

#### Summary

The foundation to Layerr's engineering success will be secure, gas efficient NFT contracts. A solidity dev joining Layerr will be expected to automate the process of contract deployment for our users (not unlike [origin protocol](https://etherscan.io/address/0x1cbe25531de1c75ac382edcbde0249be146b745a#code)). For this assessment, writing a simple NFT contract will suffice.

#### Requirements

- The contract should be able to support 3 different minting phases: closed, presale, and public sale
- Presale period should use some mechanism to check if the address attempting to mint is registered for the presale, and there should be a cap on the number of NFTs that address can mint.
- Include functionality to update certain contract parameters, like the price of the NFT, the state of the sale, the presale list (depending on the implementation), etc.

#### Goal

Design and code an NFT contract, take all the assumptions you need to move forward.

You can use any development tools you prefer: Hardhat, Truffle, Brownie, Solidity, Vyper.

Useful resources:

- Solidity Docs: https://docs.soliditylang.org/en/v0.8.4
- Educational Resource: https://github.com/austintgriffith/scaffold-eth
- Basic How-To Deploy: https://medium.com/coinmonks/5-minute-guide-to-deploying-smart-contracts-with-truffle-and-ropsten-b3e30d5ee1e

### 2) Write tests

Make sure that all your code is tested properly

### 3) Deploy your contract

Deploy the contract to the Rinkeby testnet. Keep record of the deployed address.

Faucet for rinkeby ETH: https://faucets.chain.link/rinkeby

Bonus:

- Verify the contract in Etherscan

### 4) Interact with the contract

Create a javascript script to call contract functions and mint an NFT.

_You can use any library you prefer: Ethers.js, Web3.js
