# p3-udacity-supplychain

# Truffle v5.0.2
# Solidity v 0.5.0 (solc-js)
# Node v 12.14.1
# Web "^1.6.1"

# Rinkeby testnet

# Contract Name : Supplychain
contract address   0xAb9B637Ea8A57290197F339E26A2fd5051112749
account  0xDA2C8DEa7Fba41E57e814a829A733fF944CE5A7A
transaction hash
0x2394df7b6220d6730431b1bc38afdd2cb5ba063cab14fb7be0d3b6e5ecded315

# Contract Name : ConsumerRole
contract address   0x0a3CaE7eB0e14E49A739F4D203E8b6f9A465C89f
account  0xDA2C8DEa7Fba41E57e814a829A733fF944CE5A7A
transaction hash
0xae17cb1d02e3db5f8bfecf145e9f9146bfe8e2485951698ec50f8a3fe38d79f3

# Contract Name : RetailerRole
contract address   0x58dbB496c9036Bc6a4751E0dd15DB21c402eA8ee
account  0xDA2C8DEa7Fba41E57e814a829A733fF944CE5A7A
transaction hash
0xd66aafc91cc4703c66043d3a9c2a8ed7c5b0661c2724031ea97050cce23d23bf

# Contract Name : DistributorRole
contract address    0x27d389DF06A95a675EB0dB069B9759ba3eF20e84
account  0xDA2C8DEa7Fba41E57e814a829A733fF944CE5A7A
transaction hash
0x1d7a8f81a6a8cac83aa18fe3e08c6f2e57f5d1625e1dc846c8eb786844162540

# Contract Name : FarmerRole
contract address    0x5D2aA0e2AcF65214AF4eb6fb18Ba67d916E350F8
account  0xDA2C8DEa7Fba41E57e814a829A733fF944CE5A7A
transaction hash
 0x4e15c4c9a859e1e14e51510ffa73aba9ec0c54049f977807e598209c03dd8b57



### Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-gui, Truffle and enabled MetaMask extension in your browser.

```
Give examples (to be clarified)
```

### Installing

> The starter code is written for **Solidity v0.5.0**. At the time of writing, the current Truffle v5 comes with Solidity v0.5 that requires function *mutability* and *visibility* to be specified (please refer to Solidity [documentation](https://docs.soliditylang.org/en/v0.5.0/050-breaking-changes.html) for more details). To use this starter code, please run `npm i -g truffle@5.0.2` to install Truffle v5 with Solidity v0.5.0. 

A step by step series of examples that tell you have to get a development env running

Download Zip in this repository:

```
 https://github.com/udacity/nd1309/tree/master/course-5/project-6
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-gui  "tape nuclear session loan wall gesture tone advice dentist elbow flight fetch"
```



```
truffle compile
```
This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-gui:

```
truffle migrate
```

Your terminal should look something like this:

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS

## IPFS IS NOT USED IN THIS PROJECT
