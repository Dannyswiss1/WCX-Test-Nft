# NFTStore Smart Contract

## Description
NFTStore is a simple smart contract designed to facilitate the creation, sale, and listing of non-fungible tokens (NFTs) on the Ethereum blockchain. It inherits from OpenZeppelin's ERC721URIStorage contract to implement the ERC721 standard for NFTs with token URI support.

## Features
- Minting NFTs: Users can mint new NFTs with unique token IDs, token URIs, and prices.
- Buying NFTs: Users can purchase NFTs by paying the specified price to the owner of the token.
- Listing NFTs: Token owners can list their NFTs for sale by specifying a price.

## Contract Overview
- **NFTStore Contract**: Inherits from ERC721URIStorage and provides functionalities for minting, buying, and listing NFTs.
- **Token Prices Mapping**: Maps token IDs to their respective prices.
- **Token Listings Mapping**: Maps token IDs to their listing status.
- **Owner**: Stores the address of the contract owner.

## Usage
### Minting NFTs
To mint a new NFT, call the `mintNFT` function with the recipient's address, token URI, and price.

### Buying NFTs
To purchase an NFT, call the `buyNFT` function with the token ID you want to buy. Make sure to send enough Ether to cover the token's price.

### Listing NFTs
To list an NFT for sale, call the `listNFT` function with the token ID and the desired price. Only the owner of the token can list it for sale.

## Installation
To deploy and interact with the NFTStore contract, you'll need an Ethereum development environment and a tool like Hardhat or Truffle. You'll also need to install dependencies such as OpenZeppelin contracts.

## Contributors
- [Daniel Joseph]
- [Dannyswiss](https://twitter.com/Tiya_JD)
