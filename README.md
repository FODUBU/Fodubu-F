FODUBU Ecosystem — Token Documentation & Validator Network

Powering Trade Globally with Community & Pi Network

Welcome to the official documentation repository for the FODUBU Ecosystem token project. This repository provides public documentation, environment-specific token metadata, allocation records, and technical resources for the development and verification of the FODUBU ecosystem.

FODUBU stands for Force de Développement et Ubuntu au Burundi. Its mission is to support community-driven economic development through interconnected commerce, environmental sustainability, agriculture, and digital services.

This repository is intended to promote transparency, responsible development, and clear separation between testnet experiments and production deployments.

«Important: Publishing documentation or metadata does not create, mint, issue, register, or verify a token. Token supply, ownership, distribution, validator status, and network compatibility must be established and verified using the relevant network and its supported tools.»

---

🌐 1. Official Websites and Environments

Mainnet — FODUBU Global Trade

Website: https://trade.fodubu.com

The mainnet environment is intended for the production FODUBU ecosystem and its planned utility token, F.

The production environment must use its own verified network configuration, token or contract identifiers, transaction records, and allocation controls.

Mainnet documentation must be labelled as planned until the corresponding token issuance, supply, and distribution have been independently verified.

Testnet — FODUBU Developer and Validator Documentation

GitHub Pages: https://fodubu.github.io/Fodubu-F/

The testnet environment is intended for technical validation, development, integration testing, and documentation.

The test token is designated:

- Name: FODUBU Ecosystem Test Token
- Symbol: FTEST
- Intended total supply: 100,000 FTEST
- Purpose: Technical testing only
- Production purchases: Not permitted
- Production rewards: Not permitted

The stated supply is an intended configuration, not proof of the actual on-chain supply.

Testnet assets must remain separate from production assets, accounting, rewards, and transaction records.

---

🪙 2. Token Overview

FODUBU maintains separate documentation for the planned production token and the test token.

Property| Mainnet token| Testnet token
Name| FODUBU Ecosystem Token| FODUBU Ecosystem Test Token
Symbol| F| FTEST
Environment| Mainnet| Testnet
Intended total supply| 1,000,000,000 F| 100,000 FTEST
Primary purpose| Intended production ecosystem utility and incentives| Technical testing
Production purchases| Subject to verified implementation and policy| Not permitted
Production rewards| Subject to verified implementation and policy| Not permitted
Supply status| Must be verified on-chain| Must be verified on-chain

Token symbols are not unique identifiers. Applications must identify the relevant network and, where applicable, the issuer address or token/contract ID before accepting or processing a token.

The production token and test token must never be treated as interchangeable assets.

---

📊 3. Planned Mainnet Allocation

The following allocation describes the proposed distribution of the intended 1,000,000,000 F mainnet supply.

Allocation category| Percentage| Planned amount
Initial circulating allocation (TGE)| 10%| 100,000,000 F
Pioneer rewards| 60%| 600,000,000 F
Ecosystem liquidity| 30%| 300,000,000 F
Total| 100%| 1,000,000,000 F

Allocation principles

- Initial circulating allocation: Intended for the initial circulating supply, subject to the final issuance and distribution plan.
- Pioneer rewards: Intended to support eligible ecosystem participation and reward programs.
- Ecosystem liquidity: Intended to support the ecosystem's planned liquidity requirements, subject to the applicable implementation and controls.

Vesting, eligibility, release schedules, liquidity management, and distribution must be implemented through the appropriate operational systems or supported on-chain mechanisms.

The percentages above document the proposed tokenomics. They do not establish that these amounts have already been issued, distributed, locked, or placed into liquidity.

---

🧪 4. Testnet Allocation

The intended testnet allocation is 100,000 FTEST, allocated entirely to technical testing.

Allocation category| Percentage| Intended amount
Smart contract and system testing| 100%| 100,000 FTEST
Total| 100%| 100,000 FTEST

Testing may include:

- Smart contract functionality.
- Token transfers and transaction handling.
- API integration and backend validation.
- Network configuration and transaction verification.
- Technical integration and error handling.

Testnet restrictions

FTEST is intended exclusively for testnet technical validation.

- FTEST must not be accepted as payment for production ecosystem products or services.
- FTEST must not be counted as a production reward or mainnet balance.
- Testnet transactions must not be reported as production transactions.
- Testnet token records must remain separate from mainnet token records.
- Testnet metadata must not be interpreted as authorization to issue production tokens.

These restrictions must be enforced by the relevant backend, transaction-processing logic, and supported contract controls. Metadata alone cannot enforce them.

---

🗂️ 5. Repository Structure

The repository is intended to keep public documentation and network metadata organized by purpose and environment.

A recommended structure is:

trade-page/
├── README.md
├── index.html
├── .nojekyll
├── .well-known/
│   ├── pi.toml
│   └── stellar.toml
├── testnet/
│   ├── token-metadata.json
│   └── allocation-metadata.json
└── mainnet/
    ├── token-metadata.json
    └── allocation-metadata.json

File descriptions

File or directory| Purpose
"README.md"| Project documentation, tokenomics, and environment policies
"index.html"| Public documentation or dashboard interface
".nojekyll"| Disables Jekyll processing for GitHub Pages
".well-known/pi.toml"| Pi-related metadata, if required by the supported Pi integration
".well-known/stellar.toml"| Stellar "stellar.toml" configuration, if the project uses Stellar and complies with its requirements
"testnet/token-metadata.json"| Intended FTEST metadata
"testnet/allocation-metadata.json"| Intended FTEST allocation
"mainnet/token-metadata.json"| Mainnet token metadata, marked planned until verified
"mainnet/allocation-metadata.json"| Intended mainnet allocation

This is a recommended structure. Only files actually committed to the repository are available for publication.

The ".nojekyll" file helps GitHub Pages publish files and directories that would otherwise be treated specially by Jekyll. It does not itself verify metadata or establish compliance with any token standard.

Standards and compatibility

Pi-related metadata and Stellar's "stellar.toml" serve different purposes. They must not be treated as interchangeable formats.

The presence of a "pi.toml" or "stellar.toml" file does not, by itself, demonstrate compliance with a particular Pi or Stellar standard. Compatibility must be confirmed against the applicable official specifications and the actual network implementation.

---

🔐 6. Repository Security and Access Control

FODUBU uses public documentation to support transparency while restricting repository modifications to authorized contributors.

Recommended repository controls:

- Visibility: Public for documentation intended for public access.
- Read access: Available to the public.
- Write access: Restricted to authorized collaborators.
- Branch protection: Use protected branches and pull-request reviews where available.
- Change review: Review token metadata, allocation changes, and network configuration changes before merging.
- Secrets: Never commit private keys, seed phrases, signing keys, passwords, API secrets, or confidential credentials.
- Deployment: Review GitHub Pages publishing permissions and the source branch before publishing changes.

Public documentation does not grant visitors permission to modify the repository or authorize them to issue tokens.

Repository permissions are also separate from validator permissions, token ownership, issuer authority, and smart contract administration.

---

🛡️ 7. Validator and Network Verification

This repository may provide documentation for developers and operators who need to understand the FODUBU project's network configuration.

However, publishing validator instructions does not register a validator or prove that a validator is operational.

Before describing any node as an official or active validator, verify the applicable network's requirements and the node's actual status.

Where applicable, verification should establish:

1. The intended network and network identity.
2. The relevant public account, issuer, or contract identifier.
3. The validity of the published configuration.
4. The actual token supply and distribution, using the appropriate network records.
5. The validator's registration and operating status, using the network's supported verification mechanism.
6. The separation of testnet and mainnet resources.

Never publish validator signing secrets or private account credentials in this repository.

---

🔌 8. Backend and Application Integration

Applications integrating FODUBU token functionality should use verified configuration rather than relying solely on public metadata.

The backend should:

- Maintain separate testnet and mainnet configurations.
- Validate network and token or contract identifiers.
- Reject FTEST in production purchase and reward flows.
- Keep testnet and mainnet balances and transaction records separate.
- Validate token-related operations on the appropriate network.
- Avoid trusting token symbols or client-supplied metadata as proof of asset identity.
- Log and monitor rejected cross-environment transactions.

Frontend validation may improve the user experience, but it must not replace backend enforcement.

Any token acceptance, distribution, or vesting mechanism must be implemented and tested using the actual supported token system.

---

🔍 9. Transparency and Verification Policy

FODUBU distinguishes between a documented plan and a verified technical state.

The following claims must only be made when supported by evidence:

- A token has been created or issued.
- A fixed supply exists on-chain.
- An allocation has been distributed.
- Tokens have been locked or vested.
- A validator is registered or active.
- A network integration meets a specified standard.
- A token is accepted by an official registry or listing service.

A metadata file may describe the intended configuration, but it is not independent proof of these claims.

Where possible, publish the relevant network identifier, public issuer or contract identifier, and verifiable transaction records once they exist and have been checked.

---

🤝 10. Project Mission

FODUBU seeks to build a community-oriented ecosystem that connects trade, agriculture, environmental sustainability, and digital services.

Its broader objective is to support sustainable economic development through transparent systems, responsible technology adoption, and community participation.

FODUBU Global Trade — The Unified Ecosystem for Sustainable Global Trade

Trade Green, Live Clean.

---

📄 11. Disclaimer

This repository provides technical and project documentation. It does not constitute a guarantee of token value, liquidity, exchange listing, network approval, validator status, or investment return.

Token names, symbols, intended supplies, and allocation plans are project-defined information unless independently established by the relevant network records.

Users and integrators should verify the actual network, issuer or contract identity, and applicable implementation before relying on token-related information.

---

Maintained by: FODUBU Ecosystem
Official website: https://trade.fodubu.com
Testnet documentation: https://fodubu.github.io/Fodubu-F/
Support: support@fodubu.com
