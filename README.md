
# Valut contract

 ## Overview

Valut contract to store ether and withdraw 


## Documentation



* To Deopsite Ether to the smart contract
```bash 
function deposite() external payable  returns(uint256) {}

```

* To Withdraw ethers from smart contract
```bash 
function withdraw() external payable  returns(uint256) {}

```

* To add the partners for royalties. Only Admin can add Partners
```bash 
function addPartners() external onlyOwner{}

```


## Smart Contracts

*  Vault contract [0xf67436B15353c37cFE70F97D5a81318514678B5B](https://kovan.etherscan.io/address/0xf67436b15353c37cfe70f97d5a81318514678b5b#code)


## Features

- A function to accept ether from the user, which will record the depositor and the amount deposited in the contract.
- A function to withdraw the ether from the contract with the following conditions:
- Cannot withdraw the amount greater than the amount deposited.
- Cannot withdraw the whole amount in one go.
- Contracts should emit an event on every deposit and withdrawal.

##  Project Setup

Clone the project

```bash
  git clone https://github.com/chetan-deshpande2/smart-contract.git

```

Go to the project directory

```bash
  cd smart-contract
```



