# Solidity smart contract for splitting profits to it's employees of a company

This repo houses solidity smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!

Following objectives are accomplished:

* Pay your Associate-level employees quickly and easily.

* Distribute profits to different tiers of employees.

* Distribute company shares for employees in a "deferred equity incentive plan" automatically.


## Smart Contract Files

* [`AssociateProfitSplitter.sol`](AssociateProfitSplitter.sol) -- This contract will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

* [`TieredProfitSplitter.sol`](TieredProfitSplitter.sol) -- This contract will distribute different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%..

* [`DeferredEquityPlan.sol`](Starter-Code/DeferredEquityPlan.sol) -- This contract models traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.
  
   
## Dependencies
Following technical components are needed to run these contracts:
* Remix IDE for contract build, compile, deploy and transact
* Local installation of Ganache - provides deve blockchain and 
* MetaMask (localhost:8545) wallet - source of gas fees and funds for contract deployment and transactions
   
  
## Instructions
* Clone the repo in your local directory $ git clone https://github.com/Roy-Tapas/ethereum-smartcontract
* Open AssociateProfitSplitter.sol in Remix IDE, compile the contract and then deploy.
* Test the deployed contract by sending a transaction as demonstrated in the following screen capture:
![Associateprofitsplitter](Images/Associateprofitsplitter.gif)
  
    
* Open Tieredprofitsplitter.sol in Remix IDE, compile the contract and then deploy.
* Test the deployed contract by sending a transaction as demonstrated in the following screen capture::
![Tieredprofitsplitter](Images/Tieredprofitsplitter.gif)


<hr style="border:2px solid blue"> </hr>

## Tapas Roy

**Email:** thisistapasroy@gmail.com