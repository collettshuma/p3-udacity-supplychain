# Truffle v5.0.2
# Solidity v 0.5.0 (solc-js)
# Node v 12.14.1
# Web "^1.6.1"

# Rinkeby testnet

# Contract Name : Supplychain
contract address   0xCB1E6f2cDd2A15a3b0E48a7c72813E924ec015C5
account  0xEA2f36027a3e3b14aB0AA1d1dc752eaEdf833301
transaction hash
0x4110a798f3bef580a2b25e238336afc11ef232848b30f4dae5e20ad69ea08881


# Contract Name : ConsumerRole
contract address   0x7f10ce692B033645307dda1F7Aca913cf6A2aE25
account  0xEA2f36027a3e3b14aB0AA1d1dc752eaEdf833301
transaction hash
 0xcfe07ed493cda429d9029734f1d9c7be0774f30658d1f637c77b6f0ee96d23cd


# Contract Name : RetailerRole
contract address   0xd1C2C83e01320270bC431Aa50D12FD1bB00f4214
account  0xEA2f36027a3e3b14aB0AA1d1dc752eaEdf833301
transaction hash
0xcb37516992ebef07ee45b971f9bce6edbbbd13ab504ef4ace05d7ec8024ddf19


# Contract Name : DistributorRole
contract address   0xA43211aa78447f31B1b0eA713a948c80c57f0B10
account  0xEA2f36027a3e3b14aB0AA1d1dc752eaEdf833301
transaction hash
 0xf8cbcb0684b63693acccbfcd422c2bdb0aa3203bd24e20207f4cf64e1b1f2bad


# Contract Name : FarmerRole
contract address    0x5DE7acdCee70A6Dd678252f3d48b7302089471E5
account  0xEA2f36027a3e3b14aB0AA1d1dc752eaEdf833301
transaction hash
  0x04e9d51469998605bb6eb151ec0a209f463e9f07c76f0d72b3a83d6d75a873f6



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
