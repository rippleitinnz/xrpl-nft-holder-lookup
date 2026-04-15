# XRPL NFT Holder Lookup

A single-page tool for querying all NFT holders for any issuing address on the XRP Ledger, grouped by collection taxon. Built as part of the OnLedger Elephant Tools suite.

## Live

https://onledger.net/nft.html

## Features

- Query all NFTs for any XRPL issuer address
- Results grouped by collection taxon with holder counts
- Resolves collection names from NFT metadata/IPFS
- Export results as CSV or JSON
- Four NZ-themed colour palettes — Fiordland, Waitomo, Kauri, Southern Alps
- Light/dark mode toggle — preference saved to localStorage

## Setup

Single static HTML file, no build step. Requires a server-side nginx XRPL proxy for the /xrpl-proxy endpoint.

## License

MIT
