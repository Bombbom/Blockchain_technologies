# 1. Blockchain_technologies
Blockchain - All

## 1.1. Table of contents
- [1. Blockchain\_technologies](#1-blockchain_technologies)
  - [1.1. Table of contents](#11-table-of-contents)
  - [1.2. Basic Blockchain Knowledge](#12-basic-blockchain-knowledge)
  - [1.3. Blockchain general knowledge](#13-blockchain-general-knowledge)
  - [1.4. Bitcoin](#14-bitcoin)
  - [1.5. Smart Contracts](#15-smart-contracts)
  - [1.6. (Ethereum) Smart Contracts Vulnerability Detection](#16-ethereum-smart-contracts-vulnerability-detection)
    - [1.6.1. Problem](#161-problem)
    - [1.6.2. Vulnerability of Smart Contract](#162-vulnerability-of-smart-contract)
    - [1.6.3. Survey](#163-survey)
    - [1.6.4. Static Vulnerability Detection Methods](#164-static-vulnerability-detection-methods)
    - [1.6.5. Dynamic Vulnerability Detection Methods](#165-dynamic-vulnerability-detection-methods)
    - [1.6.6. Machine Learning for Vulnerability Detection](#166-machine-learning-for-vulnerability-detection)
      - [1.6.6.1. Dataset: Source code - Bytecode](#1661-dataset-source-code---bytecode)
      - [1.6.6.2. Dataset: Simplified and Extract Features](#1662-dataset-simplified-and-extract-features)
    - [1.6.7. ContractWard Models](#167-contractward-models)
    - [1.6.8. BiLSTM-Attention](#168-bilstm-attention)
    - [1.6.9. Reference](#169-reference)
  - [1.7. Decentralized Learning for Malware Detection with Blockchain](#17-decentralized-learning-for-malware-detection-with-blockchain)
    - [1.7.1. Problem](#171-problem)
  - [1.8. Tools](#18-tools)

---
## Reference 

- https://roadmap.sh/blockchain
- https://www.blockchain.education/

---
## 1.2. Basic Blockchain Knowledge

:pushpin: Outline

- What is Blockchain?

> A digital database orr ledger that is distributed among the nodes of peer-to-peer network

![image](https://user-images.githubusercontent.com/108725538/203267392-687a7551-109b-4e1f-8582-b83ab8555a1e.png)


- Decentralized - Distributed - Centralized

![image](https://user-images.githubusercontent.com/108725538/203267830-5e738f9d-cfec-4441-9bc2-0051be216634.png)

![image](https://user-images.githubusercontent.com/108725538/203267930-9e9c300e-1d02-4949-9f10-606bfdab7ab7.png)

![image](https://user-images.githubusercontent.com/108725538/203268782-707959cf-2cf6-4bfb-89e3-415be7825f29.png)

- Why it matters?

- Blockchain structure
  - Nodes within P2P network
  - Properties of block & genesis block
  - Transactions within the ledger
  - The validation process - mining
  - The “consensus” within a blockchain architecture
    - Proof-of-work
- How blockchain work: Example 

![image](https://user-images.githubusercontent.com/108725538/203269843-ddbb108f-3ae6-4605-9790-caf8c8210c3c.png)

![image](https://user-images.githubusercontent.com/108725538/203270052-cac80484-f0e0-41fe-ba5e-eba40661c555.png)

- Basic Blockchain Operations
  - Bitcoin blockchain transactions 
  - Ethereum blockchain transactions
  
  
- Application and uses of Blockchain technology

![image](https://user-images.githubusercontent.com/108725538/203267465-94873e81-13ca-409f-a7ab-831de6c8cc33.png)


---
## 1.3. Blockchain general knowledge
:pushpin: Outline


---
## 1.4. Bitcoin

---
## 1.5. Smart Contracts 

---
## 1.6. (Ethereum) Smart Contracts Vulnerability Detection

### 1.6.1. Problem

- The DAO attacks
- The Parity bug


### 1.6.2. Vulnerability of Smart Contract

:book: Reentrancy

:book: Arithmetic (Integer Overflow and Underflow)

:book: Denial of Service

:book: Locked Ether

:book: Time Manipulation (Block values as a proxy for time)

:book: Timestamp Ordering (Transaction Order Dependence)

:book: Authorization through tx.origin

:book: Unhandled Exception (Unchecked Call Return Value)

:book: Access Control

:book: Bad Randomness

:book: Front-Running

:book: Short Address Attack

:book: Unknown Unknowns


### 1.6.3. Survey

- [ ] Systematic Review of Security Vulnerabilities in Ethereum Blockchain Smart Contract
- [ ] The State of Ethereum Smart Contracts Security: Vulnerabilities, Countermeasures, and Tool Support
- [ ] Survey on Blockchain based Smart Contracts: Technical Aspects and Future Research

### 1.6.4. Static Vulnerability Detection Methods

:book: Information Flow Analysis-based

:book: Symbolic Execution-based

:book: Logic Rules-based

:book: Composite Methods-based



### 1.6.5. Dynamic Vulnerability Detection Methods

:book: Fuzzing-based

:book: Validation-based

### 1.6.6. Machine Learning for Vulnerability Detection

#### 1.6.6.1. Dataset: Source code - Bytecode

- GoogleBig Query
- Verified Source code in EtherScan.io

#### 1.6.6.2. Dataset: Simplified and Extract Features

- N-grams

- Graph

- vectorized smart contract snippet 

### 1.6.7. ContractWard Models

- Reference:
  - [ContractWard: Automated Vulnerability Detection Models for Ethereum Smart Contracts](https://ieeexplore.ieee.org/document/8967006)
  - 

### 1.6.8. BiLSTM-Attention

- Reference:
  - [Towards Automated Reentrancy Detection for Smart Contracts Based on Sequential Models](https://ieeexplore.ieee.org/document/8970384)


### Related Work 


| Model | Method | Capability | Technology | Input | Output | Dataset | evaluate |
|---| ----| ---| ------| ----| ---| ---| -----|
|MANDO | Learning heterogeneous graphs | | | source code | 493 | 90.51%|

### 1.6.9. Reference 


---
## 1.7. Decentralized Learning for Malware Detection with Blockchain

- [ ] Collective Intelligence: Decentralized Learning for Android Malware Detection in IoT with Blockchain
- [ ] Record and Reward Federated Learning Contributions with Blockchain

### 1.7.1. Problem



---
## 1.8. Tools

| Name                                   | Github link                                           | Describe |
| -------------------------------------- | ----------------------------------------------------- | -------- |
| Solidity Parser                        | https://github.com/ConsenSysMesh/solidity-parser      |          |
| solidity-parser-antlr                  | https://github.com/federicobond/solidity-parser-antlr |          |
| python-solidity-parser                 | https://github.com/ConsenSys/python-solidity-parser   |          |
| solc-select                            | https://github.com/crytic/solc-select                 |          |
| py-solc                                | https://github.com/ethereum/py-solc                   |          |
| etherscan-python                       | https://github.com/pcko1/etherscan-python             |          |
| py-solc-x                              | https://github.com/iamdefinitelyahuman/py-solc-x      |          |
| SmartCheck                             |                                                       |          |
| MAIAN                                  |                                                       |          |
| ReGuard                                |                                                       |          |
| ContractFuzzer                         |                                                       |          |
| Oyente                                 |                                                       |          |
| S-gram                                 |                                                       |          |
| Vandal                                 |                                                       |          |
| Prosity                                |                                                       |          |
| MadMax                                 |                                                       |          |
| Ethereum Eclipse Attacks and Solutions |                                                       |          |
| Securify                               |                                                       |          |
| Semantic analysis framework            |                                                       |          |
| TrustChain                             |                                                       |          |
| Zeus                                   |                                                       |          |
| EtherTrust                             |                                                       |          |
| MaintiCore                             | https://github.com/trailofbits/manticore              |          |
