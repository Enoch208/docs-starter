# Nullis — Documentation

Judge- and developer-facing documentation for **Nullis**: policy-as-code for private on-chain finance on Stellar.

> Apps publish a financial policy. Users prove they satisfy it privately. Soroban executes the exact permitted action — without identifying or tracking the user.

Built with [Mintlify](https://mintlify.com). Content lives in `.mdx` files; navigation and branding in `docs.json`.

## Sections

- **Getting started** — introduction and one-command quickstart
- **How Nullis works** — the problem, architecture, `verify_and_execute`, claim-safety, the Privacy Receipt
- **Cryptography** — canonical hashes, the Noir circuit, unlinkability, revocation
- **Evidence & trust** — live testnet transactions, benchmarks, threat model, and an honest real-vs-mocked table
- **Build on Nullis** — the SDK, the CLI, and the example apps

## Links

- Product & code: https://github.com/Enoch208/nullis
- Live app: https://www.usenullis.xyz/
- Live contract: https://stellar.expert/explorer/testnet/contract/CBVZ3XJQLDFFOOVW3445TFT3UJYFLMAXZTX3IP5PEFAKHXUMCIG7F5Y7
- Demo video: https://youtu.be/__jVDiYdoAA

## Develop locally

```bash
npm i -g mint      # Mintlify CLI
mint dev           # preview at http://localhost:3000
```
