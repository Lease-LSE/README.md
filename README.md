# README.md
# Lease Coin (LSE) Metadata Repository

This repository contains the official metadata for **Lease Coin (LSE)**, a blockchain-based token built on the **Solana Network**. The metadata includes all essential information about the token, including its details, creator, and unique identifier.

## Project Overview

**Lease Coin (LSE)** is a digital asset built to provide services and help those in need. It operates on multiple blockchains, including **Solana**, with plans for future integration with other networks. This repository specifically holds the metadata for Lease Coin on the Solana network.

## Metadata Details

The metadata stored in this repository provides critical information about **Lease Coin (LSE)**, including the token's name, symbol, URI (link to its description or media), and associated creator details.

The metadata is used to represent Lease Coin on decentralized platforms and can be utilized for minting and trading.

### Key Information:
- **Token Name**: Lease
- **Token Symbol**: LSE
- **Token Mint Address**: `9zhWDhp9KdWSiE5riLjs2W6RpkDkmkuHsSUAddYmVray`
- **Creator Address**: `WLHv2UAZm6z4KyaaELi5pjdbJh6RESMva1Rnn8pJVVh`
- **IPFS URI**: [Lease Coin Media](https://ipfs.io/ipfs/bafkreia4fusaojv46euszgtjsw3pkipzgd6etptiagyx3w2gegc73gh7sq)
- **Token Standard**: 2
- **Seller Fee**: 0%

## Metadata Structure

The metadata is structured in **JSON format**. Here’s the breakdown:

- **root**: Contains key details such as `key`, `updateAuthority`, `mint`, and `data`.
- **data**: Contains the token's name, symbol, URI, seller fee, and creator information.
- **creator**: The address of the creator and their share of the token.
- **primarySaleHappened**: Indicates whether the token has been sold before.
- **isMutable**: Denotes whether the metadata is mutable (0 for immutable).

### Sample JSON Metadata

```json
{
  "root": {
    "key": 4,
    "updateAuthority": "WLHv2UAZm6z4KyaaELi5pjdbJh6RESMva1Rnn8pJVVh",
    "mint": "9zhWDhp9KdWSiE5riLjs2W6RpkDkmkuHsSUAddYmVray",
    "data": {
      "name": "Lease",
      "symbol": "LSE",
      "uri": "https://ipfs.io/ipfs/bafkreia4fusaojv46euszgtjsw3pkipzgd6etptiagyx3w2gegc73gh7sq",
      "sellerFeeBasisPoints": 0,
      "creators": [
        {
          "address": "WLHv2UAZm6z4KyaaELi5pjdbJh6RESMva1Rnn8pJVVh",
          "verified": 1,
          "share": 100
        }
      ]
    },
    "primarySaleHappened": 0,
    "isMutable": 0,
    "editionNonce": 253,
    "tokenStandard": 2,
    "collection": null,
    "uses": null
  }
}
