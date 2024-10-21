# Basic components of ReCert

The ReCert framework integrates Concordium’s secure, decentralized blockchain with IOTA’s scalable and feeless DLT. Verifiable Credentials (VCs) and Verifiable Presentations (VPs) of Self-Sovereign Identity (SSI) connect the two layer-1 platforms. The framework's key entities ensure the integrity of ReCert certificates, supported by SSI and Merkle trees.

### Key Entities in the ReCert Framework
Four entities collaborate in the ReCert framework to ensure smooth operations and integrity.

#### Advanced Prosumer Meters
These smart meters generate green energy and distinguish between grid and solar power, enabling automatic issuance of green energy certificates, reducing greenwashing.

#### Energy Distribution Registries/DSOs
DSOs manage electricity distribution. ReCert uses DLT-based registries to improve transparency and trust in energy distribution by labeling energy sources at inception.

#### Public Blockchain Ledger
IOTA Tangle acts as an intermediary DLT layer, connecting green energy sources to the public blockchain, offering scalability for small-scale producers.

#### Auditors / Verifiers
Auditors ensure the elimination of greenwashing by verifying data from prosumer meters via blockchain, decentralizing trust from central registries.

### Lifecycle of a ReCert Certificate
ReCert certificates, issued as SSI VCs, can be transferred or retired. Figure 5 shows the stages of a certificate’s lifecycle, from issuance to verification or retirement through VPs.

### ReCert Certificates and SSI
SSI is used in prosumer meters to issue ReCert certificates. These certificates are aggregated into Merkle trees, anchored in the Concordium blockchain after re-certification, ensuring secure and verifiable claims.

### Merkle Tree-based Aggregation of ReCert Certificates
The Merkle tree structure, with hashed nodes representing ReCert certificates, allows for secure, efficient certificate verification. The root hash is crucial for maintaining data integrity, making it ideal for ReCert.
