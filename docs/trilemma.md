Figure 3 illustrates the shift from distributed databases to blockchain, highlighting similarities between the CAP theorem's limitations and the blockchain trilemma. On-chain solutions enhance scalability with consensus algorithms, while off-chain approaches build on existing layer-1 solutions. This section introduces these concepts, leading to our hybrid solution.

### From Distributed Databases to DLTs
As data scales exponentially, vertical and horizontal scaling methods address computational demands. Horizontal scaling, which involves distributing loads across multiple nodes, paved the way for blockchain by adding consensus mechanisms to traditional databases. Blockchain stores data as a linked list, while more advanced DLTs, such as IOTA’s DAG, offer new structures without linked lists.

### CAP Theorem and the Blockchain Trilemma
The CAP theorem defines three properties—Consistency, Availability, and Partition Tolerance—in distributed systems, but achieving all three simultaneously is impossible. Blockchain prioritizes availability and partition tolerance, focusing on eventual consistency. Similarly, the blockchain trilemma forces trade-offs between security, scalability, and decentralization.

### Reliable Blockchain Solutions
Proof of Work (PoW) consensus, used in Bitcoin and initially Ethereum, emphasizes security and decentralization, compromising scalability. Ethereum’s transition to Proof of Stake (PoS) aims to improve scalability while maintaining reliability.

### Permissioned Blockchain Solutions
Hyperledger Fabric uses Practical Byzantine Fault Tolerance (PBFT) in a permissioned blockchain, compromising decentralization to offer scalable and privacy-focused solutions. Its consensus follows an execute-order-validate sequence.

### Scalable Blockchain Solutions
IOTA’s DAG-based consensus model prioritizes scalability and decentralization, sacrificing security. It is designed for high-volume IoT transactions, utilizing a tree-like structure instead of blockchain’s linked list, classifying it as a DLT rather than a blockchain.

### Layer-1 On-chain Solutions
Layer-1 solutions, like Kaspa, focus on scalability by eliminating block finalization times while maintaining security and decentralization. These independent ledger solutions operate at the core of the blockchain ecosystem.

### Layer-2 and Layer-3 Off-chain Solutions
Off-chain solutions, such as layer-2 and layer-3 blockchains, enhance scalability by building on existing layer-1 systems without maintaining separate ledgers. Layer-2 focuses on improving scalability, while layer-3 is tailored to specific applications.

### Our Hybrid On-chain and Off-chain Approach
ReCert integrates Concordium’s decentralized, secure layer-1 blockchain with IOTA Tangle’s scalable layer-1 solution. This hybrid approach combines both on-chain and off-chain strategies, with layer-3 modules enhancing specific functionalities. SSI links the three layers for optimal performance.
