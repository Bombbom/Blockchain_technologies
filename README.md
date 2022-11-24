# 1. Blockchain_technologies
Blockchain - All

## 1.1. Table of contents
- [1. Blockchain\_technologies](#1-blockchain_technologies)
  - [1.1. Table of contents](#11-table-of-contents)
  - [1.2. Reference](#12-reference)
  - [1.3. Basic Blockchain Knowledge](#13-basic-blockchain-knowledge)
  - [1.4. Blockchain general knowledge](#14-blockchain-general-knowledge)
  - [1.5. Bitcoin](#15-bitcoin)
  - [1.6. Smart Contracts](#16-smart-contracts)
  - [1.7. (Ethereum) Smart Contracts Vulnerability Detection](#17-ethereum-smart-contracts-vulnerability-detection)
    - [1.7.1. Problem](#171-problem)
    - [1.7.2. Vulnerability of Smart Contract](#172-vulnerability-of-smart-contract)
    - [1.7.3. Survey](#173-survey)
    - [1.7.4. Static Vulnerability Detection Methods](#174-static-vulnerability-detection-methods)
    - [1.7.5. Dynamic Vulnerability Detection Methods](#175-dynamic-vulnerability-detection-methods)
    - [1.7.6. Machine Learning for Vulnerability Detection](#176-machine-learning-for-vulnerability-detection)
      - [1.7.6.1. Dataset: Source code - Bytecode](#1761-dataset-source-code---bytecode)
      - [1.7.6.2. Dataset: Simplified and Extract Features](#1762-dataset-simplified-and-extract-features)
    - [1.7.7. ContractWard Models](#177-contractward-models)
    - [1.7.8. BiLSTM-Attention](#178-bilstm-attention)
    - [1.7.9. Related Work](#179-related-work)
    - [1.7.10. Reference](#1710-reference)
  - [1.8. Decentralized Learning for Malware Detection with Blockchain](#18-decentralized-learning-for-malware-detection-with-blockchain)
    - [1.8.1. Problem](#181-problem)
  - [1.9. Smart Contracct security in Blockchain - Workshop](#19-smart-contracct-security-in-blockchain---workshop)
  - [1.10. Tools](#110-tools)

---
## 1.2. Reference 

- https://roadmap.sh/blockchain
- https://www.blockchain.education/


:book: Book

- Mastering Bitcoin Programming the Open Blockchain
- The Blockchain Developer by Elad Elrom
- Mastering Ethereum Building Smart Contracts and DApps
- Mastering Blockchain Distributed ledger technology, decentralization, and smart contracts explained (Imran Bashir)

:book: Paper

- 
- 

:book: Youtube

- 
- 

:book: Github

- 
-

---
## 1.3. Basic Blockchain Knowledge

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
## 1.4. Blockchain general knowledge
:pushpin: Outline


---
## 1.5. Bitcoin

---
## 1.6. Smart Contracts 

---
## 1.7. (Ethereum) Smart Contracts Vulnerability Detection

### 1.7.1. Problem

- The DAO attacks
- The Parity bug


### 1.7.2. Vulnerability of Smart Contract

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


### 1.7.3. Survey

- [ ] Systematic Review of Security Vulnerabilities in Ethereum Blockchain Smart Contract
- [ ] The State of Ethereum Smart Contracts Security: Vulnerabilities, Countermeasures, and Tool Support
- [ ] Survey on Blockchain based Smart Contracts: Technical Aspects and Future Research

### 1.7.4. Static Vulnerability Detection Methods

:book: Information Flow Analysis-based

:book: Symbolic Execution-based

:book: Logic Rules-based

:book: Composite Methods-based



### 1.7.5. Dynamic Vulnerability Detection Methods

:book: Fuzzing-based

:book: Validation-based

### 1.7.6. Machine Learning for Vulnerability Detection

#### 1.7.6.1. Dataset: Source code - Bytecode

- GoogleBig Query
- Verified Source code in EtherScan.io

#### 1.7.6.2. Dataset: Simplified and Extract Features

- N-grams

- Graph

- vectorized smart contract snippet 

### 1.7.7. ContractWard Models

- Reference:
  - [ContractWard: Automated Vulnerability Detection Models for Ethereum Smart Contracts](https://ieeexplore.ieee.org/document/8967006)
  - 

### 1.7.8. BiLSTM-Attention

- Reference:
  - [Towards Automated Reentrancy Detection for Smart Contracts Based on Sequential Models](https://ieeexplore.ieee.org/document/8970384)


### 1.7.9. Related Work 


| Model | Method | Capability | Technology | Input | Output | Dataset | evaluate |
|---| ----| ---| ------| ----| ---| ---| -----|
|MANDO | Learning heterogeneous graphs | | | source code | 493 | 90.51%|

### 1.7.10. Reference 


---
## 1.8. Decentralized Learning for Malware Detection with Blockchain

- [ ] Collective Intelligence: Decentralized Learning for Android Malware Detection in IoT with Blockchain
- [ ] Record and Reward Federated Learning Contributions with Blockchain

### 1.8.1. Problem
Ngữ cảnh:
- Nhiều dữ liệu với hình thức khác nhau (mạng xh, mẫu mua hàng, hồ sơ chăm sóc sức khoẻ,..) của người dùng bị thu thập và sử dụng phân tích dữ liệu cho ML
- Cho đi nguồn dữ liệu mà không có phần thưởng
- Tổ chức có toàn quyền truy cập vào dữ liệu đó vào đó -> có thể là hành vi xâm nhập quyền riêng tư

sử dụng Federated Learning: phương pháp giảm thiểu vấn đề quyền sở hữu và quyền riêng tư
- gửi training model cho người dùng để đào tạo trên dữ liệu cục bộ của họ
- người dùng gửi lại weights để cập nhật mô hình
-> Người dùng không bao giờ tiết lộ dữ liệu cá nhân cho chủ sở hữu
sử dụng Blockchain: - để tạo điều kiện thuận lợi cho việc tải lên (uploading) và theo dõi các bản cập nhật từ người dùng và thưởng cho người dùng dữ liệu mà họ đã sử dụng trong tính toán 
			  - hiển thị các bản cập nhật không thể thay đổi nên an toàn
-> kết hợp quyền riêng tư và bảo mật dữ liệu cùng với phần thưởng cho các video tải lên khiến hệ thống trở nên phổ biến, thu thập được nhiều dữ liệu hơn
sử dụng EOS blockchain và IPFS để ghi lại các bản cập nhật đã tải lên và thưởng cho người dùng dựa trên chi phí đào tạo
đề xuất sơ đồ CSVES để chỉ xác thực và thưởng cho các bản cập nhật được tải lên có giá trị thông qua SC
Triển khai đơn giản với Python và Hyperledger Fabric để xác minh tính khả dụng của hệ thóng

Các model hiện có:
BlockFL sử dụng blockchain, thưởng cho người dùng cho các bản cập nhật cục bộ tỷ lệ thuận với số lượng điểm cục bộ (local data points) 
DeepChain đề xuất 1 cơ chế blockchain dựa trên khuyến khích để thưởng /trừng phạt cho người tham gia trung thực/không trung thực
-> Không đúng với thực tế
....
=> Hạn chế của các model trên là không chính xác hoặc không hiệu quả trong việc thưởng cho những đóng góp của người dùng và thiếu khả năng mở rộng dữ liệu trên blockchain


EOS blockchain: - một public blockchain không có phí giao dịch -> khuyến khích người dùng sử dụng
		    - sử dụng set 21 producers để tạo các block đồng thời, tạo blockchain có khả năng mở rộng có thể xử lý hàng triệu giao dịch mỗi giây
	
Hạn chế của người dùng thông qua SC:
- Ngay cả khi chỉ tải gradient lên thì chủ sở hữu O hoặc bên khác vẫn có thể suy ra dữ liệu của người dùng
- mặc dù sử dụng public blockchain nhưng toàn bộ gradients và training model đều không có trên blockchain -> ẩn (hidden)
- Quyền riêng tu của mô hình đào tạo đạt được thông qua sử dụng Paullier's Cryptosystem - một sơ đồ mã hoá homomorphic được sử dụng trong học máy phân tán
- Quyền riêng tư của gradient đặt được bằng cách tải toàn bộ gradient lên off-chain trên IPFS mà chỉ O mới có thể truy cập được

Proof of Concept: tìm cách trả lời liệu một blockchain có thể hoạt động với triển khai FL trong Python để ghi lại và thưởng cho các record and reward gradients uploads hay không

### Mô hình
![image](https://user-images.githubusercontent.com/108725538/203587328-a5abe2d7-ad54-4f88-ad46-f42a41ccb87e.png)

![image](https://user-images.githubusercontent.com/108725538/203587407-c34fc618-aef3-493c-9a02-a67eb18f77d8.png)


![image](https://user-images.githubusercontent.com/108725538/203587434-e14dff02-30b7-4f1f-9fda-b7c3940306c2.png)

- System and Blockchain Architecture
- Global Model
- Smart Contracts
- System Design and Workflow
- Data Validity and Quality
- Restrictions on Users via Smart Contracts
- PROOF OF CONCEPT

:pushpin: Reppositories Project 

---
##  1.9. Smart Contracct security in Blockchain - Workshop 

- Anh Trần Ngọc Tín và Nguyễn Minh Quang, BK HCM
- Verichains 
  - https://www.verichains.io/publications
- Solidity basic
- Common vulnerabilies
- https://blog.verichains.io/
- https://github.com/verichains/public-audit-reports
- https://www.verichains.io/
- https://www.linkedin.com/company/verichains/


---
## 1.10. Tools

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
