# excel-vba-blockchain-sim

## description

Simple blockchain simulation to explain some stuff:
- what is a block (chain)
- what is a header
- what are transactions
- what is a merkle tree
- what's the hash for
- what's a nonce and why do we need it
- who needs consensus
- why takes mining a block so long and validating it is quick and easy
...

You can calculate the nonce for some blocks with different difficulty to show the time factor and explain the Byzantine Generals Problem.
You can validate transactions and the blocks.

The goal was to have a simple, easy to explain code.

I tried so simplify things without loosing the logic and mechanic of a blockchain.
Feedback on improvements welcome!

Things I would like to add:
Have one tab for a transaction memory pool
Have some nodes, each on a own tab
Synchronize those nodes somehow


## preprequisites

The current standard way to calc sha256 in the code is the usage of a .NET 3.5 lib. Make sure .NET 3.5 is enabled in your Windows 10 Features (.NET 4.something is NOT sufficient). 
Alternatively use the class clsSHA256 to calc on foot. It needs only two changes in the code to use it instead of the lib. Its just slower.

## usage

add some transactions. press "calculate block hash"
