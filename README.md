# opensea-clone

Uncomplete OpenSea-clone project: Contract and Frontend finished

This project was done using Solidity for contract creation and React for Front-end development
Mocha for testing
Truffle for contract environment along with Web3, ether and Solc libraries

Contract:

For contract compilation: truffle compile
For contract deployment: node deploy.js

.env:

MNEMONIC= Your metamask 12-word Mneomic phrase
INFURA_API_KEY= Infura RPC URL
CONTRACT_ADDRESS= Deploy the contract and use the address given
PINATA_API_KEY = Your Pinata API Key from the website
PINATA_API_SECRET = Your Pinata API Secret Key from the website

testing:

Contract testing: truffle test
Pinata testing: node storage.test.js
