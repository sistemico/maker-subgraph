# Maker Subgraph
[Maker](https://makerdao.com) is comprised of a stablecoin, collateral loans, and decentralized governance.

## Events and Contracts

The Maker subgraph currently only tracks DAI, as the Graph Node needs to support anonymous functions before events in the CDP contracts can be tracked. This support will be added soon.

The SaiVox contract is not that important, so it is left out. It focuses on keeping the value of DAI near $1.00, by calling to third party price providers. This subgraph focuses more on DAI and CDPs so this isn't needed.

The SaiTop contract is not used either. This contract emits events when global settlement happens. Global settlement has never happened.

## Setting up the Subgraph

Please refer to the documentation https://thegraph.com/docs/quick-start for details on deploying a subgraph, and using the hosted service.

These docs https://github.com/graphprotocol/graph-node/blob/master/docs/getting-started.md will also help, especially with deploying your subgraph locally. 


## Getting started with querying 
Below are a few ways to show how to query the uniswap-subgraph for data. The queries show most of the information that is queryable, but there are many other filtering options that can be used, just check out the [querying api](https://github.com/graphprotocol/graph-node/blob/master/docs/graphql-api.md). These queries can be used locally or in The Graph Explorer playground.

### Querying The Maker Subgraph
> TODO