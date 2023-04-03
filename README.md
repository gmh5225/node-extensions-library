# Tenderly Node Extension Library

This library is a collection of Tenderly Node Extensions. It is used to extend the Tenderly Web3 Gateway (Node-as-a-Service) with additional functionality.

Node Extensions is a game-changing enhancement to our existing production node. It allows devs to create custom JSON-RPC method names and write custom JS/TS code snippets, which will be executed each time the method is called. It’s like having your very own sorcerer’s apprentice working behind the scenes! 🧙‍

## How to use

TBD

## Node Extension Examples

This is a Node Extension Starter. You can use this example as a starting point for your own Node Extension.

- [node-extension-starter](./node-extension-starter) - A Node Extension that gets the current block number

Here are examples of Node Extensions that you can use in your projects:

- [chainlink-price-feed](./chainlink-price-feed) - A Node Extension that allows you to query Chainlink Price Feeds
- [pm-can-sponsor-user-operation](./pm-can-sponsor-user-operation) - A Node Extension that checks whether a User Operation can be sponsored by Pimlico's Paymaster service on behalf of a third-party dapp
- [pm-sponsor-user-operation](./pm-sponsor-user-operation) - A Node Extension that asks Pimlico's paymaster to sponsor the submitted User Operation on behalf of the wallet
- [pm-supported-entry-points](./pm-supported-entry-points) - A Node Extension that returns the list of entryPoint contracts that are supported on that chain
- [polygon-block-author](./polygon-block-author) - A Node Extension that returns the block author for a given block number on Polygon (Matic) network
- [simulate-send-transaction](./simulate-send-transaction) - A Node Extension that allows you to simulate a transaction before sending on-chain
