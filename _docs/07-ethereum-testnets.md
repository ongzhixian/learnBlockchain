# Ethereum testnets

Ethereum testnets

Ethereum has four public testnets. 
Each testnet has a different deployment method and process. 
The testnets stage and test applications in a live public environment before they deploy the applications to the mainnet.

Testnets use either proof of work (PoW) or proof of authority (PoA) consensus protocols to determine how to add new blocks of transactions to the network.
Here's a quick overview of each protocol:

1.  PoW: A mining rig solves a cryptographic hashing problem to mine a new block and decide which transactions are part of that block.
2.  PoA: Block validators verify their identity on a network to decide which transactions become part of the next block in the chain.

Testnets require test ether. 
Test ether is free, and you can access it from faucets. 
You provide faucets with an account address to receive a certain amount of test ether.

Faucets have become the primary way to get test ether for a testnet. 
The community manages public test networks for the benefit of developers and testing. 
Faucets protect the testnet from spam attacks because the ether is controlled by trusted parties.

## Testnet comparison

There are 4 testnets.

Ropsten
Kovan
Rinkeby
Goerli

Ropsten 
    Use PoW consensus protocol. 
    It's closest to the mainnet in functionality. 
    Ropsten is named after a Swedish subway station and has been around since 2016. 
    Some say it has the best reproduction of the conditions on the mainnet.

Kovan
    Use PoA testnet 
    Named after a subway station in Singapore. 
    Its ether must be requested from the faucet and is controlled by trusted parties. 
    Because of this property, Kovan is immune to spam attacks.

Rinkeby
    A PoA testnet started by the Ethereum team in April 2017. 
    It's named after a metro station in Stockholm.

Goerli
    A PoA cross-client testnet 
    Named after a Berlin subway station. 
    This testnet aims to be widely usable across various clients. 
    It's robust enough to guarantee consistent availability. 
    It began with the Goerli Initiative in 2018.


Clients:
https://nethermind.io/
https://geth.ethereum.org/
https://openethereum.github.io/


Common Ethereum APIs:

## Infura

The Infura API suite provides instant access over HTTPS and WebSockets to the Ethereum and IPFS networks. 
Use this intuitive interface to connect to the endpoints of all testnets. 
Infura supports both Truffle Suite and the Visual Studio Code Blockchain development kit for Ethereum.

## MetaMask

When you deploy to a testnet or the mainnet, the MetaMask client provides a robust interface and wallet that connects to and interacts with Ethereum blockchains.

Using MetaMask to send ether and tokens on a testnet is straightforward. 
The client provides an easy interface to select and use different Ethereum networks. 
When you need to interact with development networks, MetaMask simplifies connecting to localhost 8545 or custom RPC so you can connect with Ganache and Truffle. Similarly, MetaMask has predefined connections to the public testnets and the mainnet.


# Reference

https://docs.microsoft.com/en-us/learn/modules/blockchain-ethereum-networks/2-public-networks
