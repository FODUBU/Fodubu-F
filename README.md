# FODUBU Ecosystem: Token 'F' Documentation & Validator Network

Welcome to the official documentation and validator node repository for the FODUBU Ecosystem. This repository hosts the static pages and network metadata for the unified commerce token "F", powering FODUBU Mall, SETRA Eco, and TRACO Agri.

## 🌐 Environments

To ensure strict compliance with PiRC-101/207 and Stellar SEP-0001 standards, our metadata and network configurations are isolated:

* **Mainnet Portal:** [www.fodubu.com](https://www.fodubu.com)
  * Contains the live Mainnet `.well-known/pi.toml` metadata.
* **Testnet & Validator Portal:** [fodubu.github.io](https://fodubu.github.io)
  * Hosted via this `trade-page` repository.
  * Dedicated to developer testing, node validator instructions, and Testnet `.well-known` configurations.

## ⚙️ Repository Structure

This repository uses GitHub Pages to serve static documentation and TOML configurations. The `.nojekyll` file at the root ensures that the hidden `.well-known` directory is strictly processed and exposed to network indexers.

```text
/
├── CNAME                  # Routes traffic to trade.fodubu.com
├── .nojekyll              # Bypasses default GitHub Pages Jekyll processing
├── index.html             # Validator dashboard and testnet documentation UI
└── .well-known/
    ├── pi.toml            # Testnet PiRC compliance metadata
    └── stellar.toml       # Testnet Stellar SEP-0001 compliance metadata
