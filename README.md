# 🧱 Mini Blockchain Project

This is a basic blockchain implementation written in Java. It demonstrates the core concepts of a blockchain including blocks, transactions, mining with proof-of-work, and blockchain validation.

## 🚀 How It Works

1. **Block**:
   - Each block contains a list of transactions, a timestamp, the hash of the previous block, and its own hash.
   - The block is "mined" by solving a computational puzzle (proof-of-work).

2. **Blockchain**:
   - The blockchain is a chain of blocks, where each block contains a list of transactions and a hash pointing to the previous block.
   - The blockchain starts with the **genesis block** (the first block), and additional blocks are added via mining.

3. **Transaction**:
   - A transaction represents a transfer of funds between two parties (a sender and a receiver).
   - Transactions are added to blocks, and the blockchain ensures their validity using cryptographic signatures.

4. **Proof of Work**:
   - This mining mechanism requires solving a computational puzzle to add blocks to the blockchain. The puzzle ensures that new blocks are added in a decentralized and secure manner.

5. **Blockchain Integrity**:
   - The blockchain is validated by checking the hashes of each block. If any block is tampered with, the chain will be invalidated.

## 🖼️ Example Output

```plaintext
   Wallet Balance Before Transaction:
   Wallet A: 1000.0
   Wallet B: 0.0

   Transaction: 50.0 from Wallet A to Wallet B

   Mining Block 1...
   Block #1 added to the chain with hash: 0000a2f34e9...

   Wallet Balance After Transaction:
   Wallet A: 950.0
   Wallet B: 50.0

   Blockchain Validity: true

```

## 📦 Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Tihmer/Simple-BlockChain.git
   cd Simple-BlockChain
