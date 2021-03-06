# Truffle Suite

Truffle is a suite of tools for building and testing smart contracts.
Use the Truffle tool suite to test Ethereum contracts before you deploy them to public ledgers and incur real costs. 
To make your work as a developer easier, develop locally. 
The tool suite includes Truffle, Ganache, and Drizzle. 

1.  Truffle
    Build contracts
2.  Ganache (pronounce- guh-nash)
    Local blockchain for development
3.  Drizzle
    Drizzle makes writing dapp user interfaces more predictable and easier through its collection of front-end libraries.


## Truffle

Truffle is the most popular development environment and testing framework for Ethereum. 


### Install 

You can install Truffle by using the node package manager. In the terminal, type:

`npm install -g truffle`

To confirm that Truffle is installed, type:

`truffle`

There is also a "Trufflefor VS Code" extension by ConsenSys Software Inc"

## Ganache

The most popular local Ethereum blockchain is Ganache. 
You can use Ganache to develop, deploy, and test in a safe and deterministic environment. 
Ganache can be used from the command line, programmatically via Node.js, or in the browser.

### Install

npm install ganache --global

After Ganache is installed, run:

ganache


By default, the blockchain generated by ganache has 10 generated accounts. 
Each account:
    1.  receives 100 test ether to use. 
    2.  has a corresponding private key. 
    3.  has a mnemonic. A mnemonic is a unique 12-word phrase that provides access to the wallet and allows transactions to be made from the account.

The output also displays the blockchain's address. 
We'll use this address to connect to the blockchain. 
By default, the address is 127.0.0.1:8545.



## Drizzle

Drizzle is built with JavaScript. 

Has great support for React, and there's also an option to use Vue.js or Angular.

Drizzle helps to synchronize and manage smart contract data. 
This synchronization is significant so that the blockchain data stays aligned with your app interface. 
It uses a Redux store. 
Redux is a state container for JavaScript apps that makes it easy to track all transactions. 
Plus, it helps applications behave consistently for users and any environment they use.

Drizzle apps interact with smart contacts by using a JSON-RPC layer called the Web3 API.

JSON-RPC is a remote procedure call (RPC) protocol. 
It's stateless, lightweight, and uses JSON for the payload. 
JSON-RPC specifies a set of data structures and defines the rules around processing those structures.

To talk to an Ethereum node from a JavaScript application, the Web3 API is needed. 
Web3 is the Ethereum-compatible JavaScript API and has bindings that are built through the JSON-RPC protocol.

Drizzle is modular, which means you can use as much or as little of the library portions as you want.

The three core packages are:

1.  drizzle: Library you use to instantiate web3, account, and contract. You also use the library to connect the smart contracts to the dapp.
2.  drizzle-react: Library that makes usable React components by abstracting the core Drizzle functionality.
3.  drizzle-react-components: Library that includes user interface components for common dapp functions. 
    This library includes the ContractData, ContractForm, and LoadingContainer React components.

```
import { Drizzle } from "@drizzle/store";
import { newContextComponents } from "@drizzle/react-components";
import { DrizzleContext } from "@drizzle/react-plugin";
```



## Truffle commands

Common commands:

`truffle compile`
`truffle migrate`
`truffle test`

Truffle v5.5.16 - a development framework for Ethereum

Usage: truffle <command> [options]

Commands:
  cli.bundled.js build      Execute build pipeline (if configuration present)
  cli.bundled.js compile    Compile contract source files
  cli.bundled.js config     Set user-level configuration options
  cli.bundled.js console    Run a console with contract abstractions and
                            commands available
  cli.bundled.js create     Helper to create new contracts, migrations and tests
  cli.bundled.js dashboard  Start Truffle Dashboard to sign development
                            transactions using browser wallet
  cli.bundled.js db         Database interface commands
                            blockchain
  cli.bundled.js deploy     (alias for migrate)
  cli.bundled.js develop    Open a console with a local development blockchain
  cli.bundled.js exec       Execute a JS module within this Truffle environment
  cli.bundled.js help       List all commands or provide information about a
                            specific command
  cli.bundled.js init       Initialize new and empty Ethereum project
  cli.bundled.js install    Install a package from the Ethereum Package Registry
  cli.bundled.js migrate    Run migrations to deploy contracts
  cli.bundled.js networks   Show addresses for deployed contracts on each
                            network
  cli.bundled.js obtain     Fetch and cache a specified compiler
  cli.bundled.js opcode     Print the compiled opcodes for a given contract
  cli.bundled.js preserve   Save data to decentralized storage platforms like
                            IPFS and Filecoin
  cli.bundled.js publish    Publish a package to the Ethereum Package Registry
  cli.bundled.js run        Run a third-party command
  cli.bundled.js test       Run JavaScript and Solidity tests
  cli.bundled.js unbox      Download a Truffle Box, a pre-built Truffle project
  cli.bundled.js version    Show version number and exit
  cli.bundled.js watch      Watch filesystem for changes and rebuild the project
                            automatically


# References

Ganache Quickstart
https://trufflesuite.com/docs/ganache/quickstart/