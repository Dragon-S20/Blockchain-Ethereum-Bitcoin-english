# Blockchain-Ethereum-Bitcoin-english

The characteristics of a blockchain:

A blockchain is a distributed ledger (Distributed Ledger Technology).

We say that the chain is immutable because there is not only one point of authority. In short, the distributed network is a response to the expression of "single point of authority, single point of failure".

On a blockchain, all transactions are logged

A blockchain is a set of blocks available on a distributed network

## The advantages that technology provides:

There are two major advantages to using a blockchain: its incorruptability (immutability), and its use of a distributed network.

Each block is created through the hash process. This process is generated by the hash function, which is a one-way function. All the blocks are intimately linked to each other thanks to hashes.

We can consider that the hash is the identity of a data passed in input.

There are several hash functions:

- MD5 1
- Sha1sum 2

In reality, each block consists of a unique number, as well as hashes from previous blocks: all the blocks in the chain are therefore linked to each other. There is no missing block in a chain since the block numbers follow each other with the hashes of the previous block.

The block is a storage place for hashes and helps maintain immutability (link between blocks).

Finally, you should know that a block is divided into two parts:

- A header block which groups together previous transactions and hashes 1

- A list of transactions to be recorded in block (the tx) 2

![GitHub Logo](/img/blockchain.jpeg)

To conclude, the hash is an important function which guarantees the integrity of the register. Present in each block, it therefore becomes extremely difficult to corrupt the chain.

## Consensus mechanism:

1. Proof of work (PoW):

Proof of work is the original principle implemented in the first blockchain. This principle was initially used to fight against spam.

It is an algorithmic consensus guaranteeing the integrity of the mining. Each miner must solve a more or less difficult puzzle. The difficulty will vary depending on the mining time. That is, in case of rapid mining, the next puzzles will be more difficult

The puzzle is to find a hash number greater than the one present in the block header _ (target) _. To do this, the miners will use the _nonce_ (a field which at the beginning of the problem solving will be empty) and write down everything that will be useful for solving the problem.

The miner who solves the problem will get a reward for the work done.

2. Proof of stake (PoS):

The proof of stake is a concept created by ethereum to meet the large demand for energy demanded by the PoW.
With the proof of stake, the creator of the next block in the chain is the one who left a deposit of minimum 32ETH.

Ultimately, Ethereum is changing the paradigm of the trust mechanism, by implementing this new concept. The integrity of the chain is then guaranteed only by those who have an interest in it (large amount of ETH).

3. Mining:

Mining is an expensive process. It is performed by minors attracted by the reward and high transaction costs. The higher the transaction fees offered, the faster the mining of a transaction will be.

4. The costs:

The Bitcoin blockchain uses transaction fees (or gas for Ethereum) to pay miners for their work. There is a charge to modify the channel, to carry out an information process.

This system was created to protect the chain from network overload.

## Asymmetric encryption:

Asymmetric encryption, not to be confused with cryptography (poor translation from English), is defined by the use of a private key and a public key.

The private key, which must remain secret, is defined randomly and is therefore generated by an algorithm (the ecdsa). This algorithm works like an elliptical curve.

The generated private key will pass a function which will be the source of the public key.

The public key can be freely shared on the network. From this key will be created an address used during transactions.

Each transaction contains a message, and a signature generated by the sender's private key.

## The particularities of Ethereum:

There are 3 big differences between the Ethereum and Bitcoin blockchain:

- Ethereum uses a virtual machine (turing complete). Although there is some logic in the bitcoin script, it is much more advanced at Ethereum. The virtual machine will create a back code between 0 and 1. It is it which will be at the origin of all the operations and is even present in Ethereum nodes.

Each execution made on the network, Ethereum charges a specific cost (see link in resources to know)

- Ethereum offers the possibility of deploying smart contracts there

Ethereum introduced the concept of gas for transaction fees

## Important resources to know:

- Bitcoin white paper: https://bitcoin.org/bitcoin.pdf

- Ethereum yellow paper: https://ethereum.github.io/yellowpaper/paper.pdf

- https://ethervm.io/
