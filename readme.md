# Collection Pool

Collection Pool is a dApp that facilitates group transactions on Ethereum through the use of payment pools.

Currently, it supports Polygon and has integrated Chainlink Price Feeds and OpenZeppelin Defender.

## The smart contracts

You can find more information about the smart contracts in the contract subdirectory. Essentially, there is a factory contract for producing different pool contracts for users.

## Frontend

The dApp frontend is a nextJS website which integrates with the user’s crypto wallet to facilitate the creation of new pools via the contract factor. It also allows users to view pools and their current status, contribute to pools and embed pools onto their own website.
