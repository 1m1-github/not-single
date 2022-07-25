# not-single
zk prove that you are in a relationship without divulging with whom.

Let’s start with 1-on-1 relationships, i.e. there are 2 parties: A and B.

B publishes: H(H(B) + A), i.e. the smart contract has a state for B with this publication, which can be overwritten.

A zk prove withs via a circuit with
A, B, H(H(B) + A) is private input and they match
The smart contract would check additionally whether B’s state is H(H(B) + A) whilst A is proving that they know A and B and it matches H(H(B) + A).
The main obstacle can be the limited storage for state as the number of users explode.
