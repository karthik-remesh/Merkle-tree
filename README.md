# Merkle-tree

Merkle tree also known as hash tree is a data structure used for data verification and synchronization. 
It is a tree data structure where each non-leaf node is a hash of it’s child nodes. All the leaf nodes are at the same depth and are as far left as possible. 
It maintains data integrity and uses hash functions for this purpose.
Merkle trees are useful in distributed systems where same data should exist in multiple places.
Merkle trees can be used to check inconsistencies.
Apache Cassandra uses Merkle trees to detect inconsistencies between replicas of entire databases.
It is used in bitcoin and blockchain.
