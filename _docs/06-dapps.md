# Dapps

A dapp, or a decentralized application, uses smart contracts. 
Smart contracts run on a blockchain network and allow users to interact with the application interface through a web browser or a mobile app.

Dapps are:

1.  Decentralized. They run independently on a decentralized network and are not controlled by a centralized authority.
1.  Deterministic. They perform the same function no matter which environment runs the code.
1.  Turing complete. They can perform any action that can be coded.
1.  Isolated. They're run in a virtual environment called an Ethereum Virtual Machine. 
    That way, bugs or other problems won't affect other blocks or the normal functioning of the blockchain network.

# Benefits of dapp development

Dapps help users to interact with the blockchain network in an easy and visual way. They also provide these benefits:

1.  Zero downtime. After the underlying smart contract and app are deployed on the blockchain network, 
    the network will always be available to serve clients that want to interact with the contract.
2.  Privacy. Users don't need to provide their real-world identity to interact with a dapp.
3.  Censorship resistance. No entity on the network can prevent users from using the dapp in any way.
4.  Data integrity. Because data stored on the blockchain is immutable, bad actors can't modify or falsify data and transactions.
5.  Verifiable behavior. Smart contracts and their dapps are guaranteed to run in a predictable way without a central authority.

Augur is a platform where you can bet on things like sports, economics, politics, and entertainment. 
    The user interface allows you to trade and to view reporting on both the open and closed bets. The UI for betting is still in progress at this time.

OpenSea is a platform where you can buy, sell, and discover limited-edition goods. 
    The dapp allows users to browse items and make an offer or buy for the price listed. Users can also list their goods for sale.

Cryptokitties is a gaming dapp where you can breed, collect, and sell unique cryptographic kittens. 
    Additionally, you can do things like solve puzzles, earn rewards, and play games with your kitties.

Brave is a fast and private browser that allows you to earn tokens called BAT that can be donated to web creators, 
    and can soon be used to buy gift cards and other rewards.


# Truffle boxes

Truffle boxes are boilerplates or templates that can contain helpful modules, Solidity contracts and libraries, front-end views, and more. 
We can even get complete example dapps.

The Drizzle box help us quickly and easily build our first dapp and provide an overview of Drizzle's capabilities.

The Drizzle box comes with several out-of-the-box smart contracts to check out. 
It also comes with a simplified truffle-config.js file that's designed for development and testing.

## Drizzle box

Unboxing Drizzle results in essentially two separate projects within a single directory: a truffle project and a drizzle-react client project. If you already have experience with Truffle, the directory structure will look familiar in the area for smart contracts. The main difference is how you wire it to Web3. You also need to take configurations for modification into account.

`truffle unbox drizzle`

The Truffle Drizzle box comes with three contracts that use the Drizzle components for connecting to a dapp. 
The contracts directory contains the files ComplexStorage.sol, SimpleStorage.sol, and TutorialToken.sol. 
The Drizzle tutorial uses them.

MyComponent.js
    Creates the component for connecting the SimpleStorage, ComplexStorage, and TutorialToken smart contracts with the front end.

drizzleOptions.js
    Create an options object and pass in the desired contract artifacts for Drizzle to instantiate. 
    The options object sets up and instantiates the Drizzle store.

App.js
    App.js contains the code for the main app. 
    It requires importing React and the Drizzle libraries. 
    It must also import the component file that interacts directly with the smart contract.

