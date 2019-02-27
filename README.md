# Simple Lottery (HyperLedger Design)

<img src="https://imgur.com/JFxOnYU" width="100%" height="100%" border="5">

##### Step 1: The Application User Enrolls Organizations Certificate Authority (CA)
##### Step 2: The Application User Registers the Users
##### Step 3: The Application User calls a Function from Chaincode (Smart Contract)
##### Step 4: The Application from SDK will then Generates the Transaction Proposal
##### and sends it to the required set of Peers for endorsement. Once the Application
##### receives the sufficient number of signed proposals -
##### Step 5: The Orderer Node will receive the Transaction Proposal, the orderer will
##### arrange this Transaction Proposal to package them into a block.
##### Step 6: All of the peers connected to the orderer will be sent a copy of the new block.
##### Step 7: Each peer will now verify if transaction has been endorsed by the required organizations 
##### according to the endorsement policy of the chaincode which generated the transaction.
##### Step 8: After a peer has successfully validated each individual transaction, it updates the ledger.
##### Final Step: The strict ordering of transactions into blocks allows each peer to validate that transaction 
##### updates are consistently applied across the blockchain network.

<hr / >

## REFERENCES

### https://hyperledger-fabric.readthedocs.io/en/release-1.4/chaincode4ade.html
#####   Author: (c) HyperLedger 2019
#####   Access: February: 25, 2019
#####   Year: 2019

### https://hyperledger-fabric.readthedocs.io/en/release-1.3/txflow.html
#####   Author: (c) HyperLedger 2019
#####   Access: February: 25, 2019
#####   Year: 2019

### https://hyperledger-fabric.readthedocs.io/en/release-1.4/channels.html
#####   Author: (c) HyperLedger 2019
#####   Access: February: 25, 2019
#####   Year: 2019

### https://hyperledger-fabric.readthedocs.io/en/release-1.4/peers/peers.html
#####   Author: (c) HyperLedger 2019
#####   Access: February: 25, 2019
#####   Year: 2019

### https://hyperledger-fabric-ca.readthedocs.io/en/latest/users-guide.html
#####   Author: (c) HyperLedger 2019
#####   Access: February: 25, 2019
#####   Year: 2019
