# Week15_HW
Blockchain Development

To start the network, you will need to start both nodes by entering the following commands in a blockchain-tools folder in separate Git Bashes: ./geth --datadir node1 --unlock 0x60C7224eacF87f702050736432D4Bcb6b9Dc8Cb4 --mine --rpc --allow-insecure-unlock $ ./geth --datadir node2 --unlock 0x93c06f9612cBc9e8856EfF48f51c422d49b94CB9 --mine --port 30304 --bootnodes enode://9ba20bc6bf3c0078f2a30107251f1d5c362bae84fbbc6abef8b87495fadce763f7108e33d4c8eea387ceb242649ae08893d4c81da938ebf006a9923541dd3fb1@127.0.0.1:30303 --ipcdisable --allow-insecure-unlock

These commands will ensure the mining begins

You will be prompted to enter a password to unlock: Admin123

Please note: During genesis, existing accounts on Metamask can also be prefunded to skip the below step Once this is running, you will need to export the keystore into a web3 wallet that's compatible with localhost such as Metamask, this can be done by: Clicking the circle on the top right --> Import Account --> JSON File --> Choose File (file located in "node1/keystore") --> Enter password "Admin123"

Note: if transactions remain pending for an extended period of time, try to restart node2 by typing ctrl+c then restarting it (while node1 is running)