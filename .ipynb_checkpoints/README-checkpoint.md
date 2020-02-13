# Blockchain 18 Homework Assignment

Proof of Work Development Chain

In this activity, I will create my Genesis block using Puppeth tool bundled with the Go Ethereum. The genesis block is the first step towards creating a new blockchain!

# Creating Genesis

* In Terminal we call ./puppeth command
* After that we select network name (in our case it will be rionda89)
* Then, configure new genesis (option 2)
* Option 1 Create new genesis from scratch
* Select concensus: Etash - Proof-of-Work 
- Could not execute Proof-of-Authority as requested, since POW was covered in class

![Call Puppeth and configure genesis](Puppeth.png)

# Import from MyCrypto Wallet
* Connected to 2 accounts from MyCrypto wallet by selecting and then unlocking each account
* Specified the network ID as 1976
![Opened MyCrypto to Identify Accounts](Crypto_Wallet.png)
![Unlocked Account](Unlocked_Account.png)
![Imported Accounts](Add_Accounts.png)

# Creating Nodes
* Manage existing genesis
* Export genesis configurations
* Exit puppeth by using Ctrl+C 
* Using the geth command we create the first and second node's data directory
* Initialize and direct the nodes to use the genesis block 
![Setup Directory](Setup_Directory.png)
![Export Genesis](Create_Genesis.png)
![Create Data Directory](Create_Nodes.png)

# Starting a Chain
* Node 1 will begin mining
![Mine Node 1](Mine_node1.png)
* Node2 will be a full node that exposes an RPC port, allowing it to connect with other apps like MyCrypto
* In order to launch node 2, the enode address from node1 needs to be included in another command in a new Terminal window
![Expose RPC Port in node 2](Connect_node2.png)

# Processing transaction using MyCrypto wallet

* Created a custom node called jrionda89, using ETH, chain ID 1976
* Using the previously copied Private key, I unlocked the wallet
* Select send ether and tokens
* Confirm transaction & send
# Unfortunately, I was unable to confirm a successfuly transaction. However, I was able to complete all of the steps. However, I have been able to successfully complete other transactions since completing this assignment