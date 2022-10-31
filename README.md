# BoGoChain

A Blockchain written in Golang for education purposes.

There are 3 local servers on ports 5000, 5001 and 5002. These acts as nodes and display the current state of the blockchain. 
Mining is automaticaly performed based on a Proof Of Work algorithm with a timed loop.
Concensus is achieved when at least 2 of the 3 nodes agree on the blockchain state. The longer confirmed blockchain has priority over a shorter confirmed one.

URL "/transactions" shows the transaction pool. For example 127.0.0.1:5000/transactions.

Wallets are located on ports 8080 and 8081. For example 127.0.0.1:8080.
