# Tokens

## Two categories of blockchain tokens

Different kinds of tokens are available in blockchain, but they're usually in one of two categories:

1.  Fungible. Fungible tokens are:
        Equivalent
        Exchangeable
        Valued by how many you have

2.  Non-fungible. (NFTs) Non-fungible tokens are:
        Unique
        Distinct
        Valued by which ones you have

## Token standards

Token standards are defined in the Ethereum Request for Comments (ERCs). 
Although new standards are continuously being proposed and accepted, 
standards for four primary ERC types have been widely adopted:

1.  ERC20 (for FTs)
    The ERC20 token is the most widely known and used. 
    ERC20 is the technical standard that's used for smart contracts on the Ethereum blockchain to implement tokens.
    Any one ERC20 token is equal to any other token. 
    ERC20 tokens don't have any associated special rights or behaviors, which make the tokens useful for things like staking, currency exchange, and voting rights.

2.  ERC721 (for NFTs)
    The top solution for non-fungible tokens (NFTs). Like all other tokens, NFTs represent ownership both of virtual and physical assets. These assets are likely to include:

    Collectible items, like antiques, cards, or art
    Physical assets, like houses or cars
    Negative-value assets, like loans
    Each token is unique and has ownership and status that must be tracked.

3.  ERC777 (for FTs)
    A (richer/complex) standard that is used for fungible tokens. 
    The standard can be used for new use cases and to build on learnings from previous token standards. 
    It's backward-compatible with ERC20, which means you can interact with ERC777 tokens as if they're ERC20 tokens. 
    You can use ERC777 tokens for interactions that are more complex trades.

4.  ERC1155
    A standard that's used to manage multiple types of tokens. 
    A contract can represent multiple fungible and non-fungible tokens.

    ERC1155 draws on ideas from ERC20, ERC721, and ERC777.

    The design of the ERC1155 token type allows for massive gas savings, for a couple reasons. 
    (In Ethereum, gas refers to a fee or pricing value charged to execute transactions.) 
    First, you can use this token contract for multiple tokens, which means fewer deployments with less complexity. 
    It also has batched operations, so a single function call can be simpler and less gas-intensive.

## OpenZeppelin

OpenZeppelin is a platform that has tools you can use to write, deploy, and manage decentralized applications. 
OpenZeppelin is an open-source tool that provides reliability and security with the products it provides.

OpenZeppelin offers two products:
1.  Contracts library and 
2.  SDK

The OpenZeppelin Contracts library gives you access to a robust set of modular and reusable smart contracts for the Ethereum network. 
The smart contracts are written in Solidity. 
The main benefit of using OpenZeppelin contracts is that they have been thoroughly tested, audited, and community-reviewed.

A variety of contract types are available, including:

1.  Access Control:         Use when you want to decide who can perform actions.
2.  Tokens:                 Use to create tradeable assets.
3.  Gas Station Network:    Use when you want your users to be able to use contracts without paying for the gas (fees).
4.  Utilities:              Use when you need generic, useful tools.

Although we'll use only the token contracts in this module, it's good to be aware of the other contract resources that are available.



The SDK offers a command-line interface (CLI), so it's easier to manage smart contract development. 
You can save hours of development time by using the CLI to compile, upgrade, and deploy smart contracts. 
The CLI provides support for Ethereum and other Ethereum Virtual Machine-powered blockchains. 
The commands are intuitive and interactive to help guide you through the development process.
