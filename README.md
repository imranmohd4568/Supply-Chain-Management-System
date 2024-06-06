# Supply-Chain-Management-System

OBJECTIVE:

To make a supply chain management system which checks that the product is reaching the clients from the manufacturer with the help of distributors assuming you are working in a manufacturing company which manufactures more than ten products and is currently facing some issues in its distribution to clients.

FEATURES:

1.	To register new clients, distributors and a manufacturer (only one) to the     system, with the client and distributor depositing a security amount to a trusted third party.
2.	To improve the security of the blockchain, incorporate Proof of stake(POS) consensus algorithms. 
3.	Implementing Merkle tree to calculate the hash of all the transactions in a block and successfully mine the block with the transaction. 
4.	To view the current product status in the supply chain using a QR code. 
5.	At one time, the distributor can distribute a product to a dedicated client. Once the transaction is confirmed by both the distributor and the consumer, then only the next delivery can be taken by him/her. 
6.	A well-known issue is understood when:
 a. The distributor has dispatched the product, and the client has received   it, but the client is denying it (The client is lying, but the distributor is not).
 b. The distributor has not dispatched the product, and the client has not received it (The client is not lying, but the distributor is).



DEFINING METHODS:



PROOF OF STAKE(POS):

    The Proof of Stake (PoS) consensus method is employed in blockchain networks to reach consensus over the blockchain's current state and to validate transactions without the usage of resource-intensive mining operations. The quantity of cryptocurrency tokens that validators have and are prepared to "stake" as collateral determines who gets to produce new blocks and validate transactions in a PoS system.


SHA-256 ALGORITHM:

SHA 256 is a part of the SHA 2 family of algorithms, where SHA stands for Secure Hash Algorithm. Published in 2001, it was a joint effort between the NSA and NIST to introduce a successor to the SHA 1 family, which was slowly losing strength against brute force attacks. 
● The significance of the 256 in the name stands for the final hash digest value, i.e. irrespective of the size of plaintext/cleartext, the hash value will always be 256 bits.

                       

MERKLE TREE:

In cryptography and computer science, a hash tree or Merkle tree is a tree in which every "leaf" (node) is labelled with the cryptographic hash of a data block, and every node that is not a leaf (called a branch, inner node, or inode) is labelled with the cryptographic hash of the labels of its child nodes. A hash tree allows efficient and secure verification of the contents of a large data structure. A hash tree is a generalisation of a hash list and a hash chain. Demonstrating that a leaf node is a part of a given binary hash tree requires computing a number of hashes proportional to the logarithm of the number of leaf nodes in the tree. Conversely, in a hash list, the number is proportional to the number of leaf nodes itself. A Merkle tree is therefore an efficient example of a cryptographic commitment scheme, in which the root of the tree is seen as a commitment and leaf nodes may be revealed and proven to be part of the original commitment.
