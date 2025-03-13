# My-own-crypto

This project implements a basic blockchain for a cryptocurrency called MemeCoin, using Python and Flask. It demonstrates key concepts like mining, transactions, and decentralization. The blockchain is designed to allow nodes to communicate and synchronize with each other.

Key Features:
Blockchain Creation: A blockchain is created where each block contains proof of work, a timestamp, and transactions.
Mining: Nodes can mine blocks by solving proof-of-work problems.
Transactions: Users can add transactions to the blockchain.
Decentralization: Nodes can join the network and replace chains with the longest valid chain.
Validation: The blockchain can be validated for integrity to ensure it hasn’t been tampered with.
API Endpoints:
/mine_block: Mines a new block.
/get_chain: Retrieves the full blockchain.
/is_valid: Checks if the blockchain is valid.
/add_transaction: Adds a transaction to the blockchain.
/connect_node: Connects nodes to the blockchain network.
/replace_chain: Replaces the current chain with the longest valid chain.
This is a basic implementation designed for educational purposes, demonstrating how blockchain systems work in a decentralized environment.
