# BlockchainBasics :

## [Certificate](https://www.coursera.org/account/accomplishments/records/GYCDHPSXRUG4  "My certificate")
### [Course](https://www.coursera.org/learn/blockchain-basics/home/welcome "Offered Course")

```
This repo. contains my assignment and notes of the Blockchain Basics course offered by Buffalo University on Coursera.
```
Core topics :
# Blockhain - for decentralised, peer to peer connection
## Developing Trust:
* Validation
* Verification
* Consensus Protocol
* Immutable Recording
#### use of immutable distributed ledger
## Unspent Transaction Output (UTXO)
* Unique Identifier
* index
* amt
* optional : condition
## Transaction (Tx) 
* Refernce no. to the current transaction
* Reference to one or more input UTXOs
* Reference to one or more output UTXOs  (newly generated by the current transaction)
* Total input and output
## Genesis Block (Block0) : 
### The zeroth or first block of the block chain  
## Summary
* No. of transactions
* Output total
* Estimated Transaction
* Transaction fees
* Height
* Time stamp
* Received Time
* Relayed by
* Difficulty
* Bits
* Size
* Weight
* Version
* Nonce
* Block Reward
## Hash
* Previous Block
* Next Block
* Merkle Root
## Work of miners
* verify transactions
* Broadcast transactions
* compete to create a block
* Reacg consensus by validating blocks
* Broadcast new bolck
* confirm transactions
#### Miners perform operations designed by bolckchain proetocal

## Transaction 0
* for paying minor fees
* does not have an input UTXO
* is called coin based transaction

## Smart Contract
#### Ethereum bolckchain used the optional scripting feature to develop a full blown code execution framework called smart contract
Execution of smart contract is initiated by a message embedded in the tracnsaction

## Types of Blockchain
* only cryptocurrency - Bitcoin
* currency + Bussiness logic - Etherium
* Only Bussiness logic - Linux foundation's Hyperledger

## Categories:
* Public
* Private
* Permissioned / consortium

### Solidity for Smart Contract
#### Basic Syntax
pragma solidity ^0.40;
contract SimpleStorage {
 uint storedData;
 function set (uint x){
  storedData =x;
  }
  
  function get() constant returns (uint){
  return storedData;
  }
  }
  
  The code is rum in EVM or ethereum virtual machine
  
  #### Reference no.
  input UTXOs --> output UTXOs
  
 ## TYpes of Accounts
 * Externaly owned acc
 * Contract Acc
 
 ### Externally owned acc can transfer ethers or messages
 ### Contract accs are used to hold ethres while acting as an intermediary. 
 Eg - Caution money will be stored in the contract acc and transferred in the respective acc as per the situations and norms.
 
 #### Accounts need to pay fees for transaction. 
 These are paid in wei, a lower denominationof ether.
 
 ### 1 ether = 10^18 wei
 
 ## Transaction involves :
 * Signature of sneder authorizing transfer
 * Amount of wei
 * Message to a contract
 * Start gas (max no. of steps)
 * gas price (fee for computation)
 #### Header --> Transactions --> Runneruo headers
 
 ## Ethereum Node
 An ethereum node is a computational system representing a business entity or an individual participant.
 #### An ethereum full node hosts the software needed for transaction initiation, validation, mining, block creation, smart contract evaluation and EVM.
 ```
 A blockchain maintains both a state hash and a receipt hash
 ```
 ## Incentive Model
 #### Gas limit 
 Amount of gas available
 #### Gas spent
 Amount of gas spent on block creation
 ```
 Proof of work puzzle winner gets the transaction amount, others who solve it are know as Ommers who get a small bit of it.
 ```
 ## Securing Block chain - Verification and Validation
 ### Hashing and assymetric key encryption
 
 ## Public key cryptography algorithm
 ### Caesar Algo.
 encryption is done by shifting the alphabets by a particular distance.
 #### issue - requires transfer of key and is easy to get and hence more prone to hacking
 ## public key cryptography with two keys are used.
 A tracnsaction or a contract locked by one's private key can be opened by a public key only and vice versa.
 #### sender locks it with his private key and receiver's public key while the receiver unlocks it with his private key and sender's public key.
 ## Algorithm used for genrating key pair 
 #### ECC - Elliptic Curve Cryptography
 whereas RSA (Rivet-Shamir-Adelman) is used in various other applications such as amazon cloud.
 ## Hashing 
 transforms an arbitrary length input data to a unique fixed length value (256 bits)
 #### Algorithm is a one way function and hence collision free
 secure hash agorithm which has 2^256 possible combinations.
 ## Hashing is used to generate 
 * Account Address
 * Digital Signatures
 * Transition hash
 * State Hash
 * Receipt hash
 * Block header hash
 
 ## [Smart Contracts]( https://github.com/SanchitaMishra170676/SmartContracts  "Smart Contracts")
 
 
 

 
 
              
