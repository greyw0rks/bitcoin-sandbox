# Bitcoin Sandbox

Learn Bitcoin transactions by building one, checking its change and fee, and mining its first confirmation.

[Open Bitcoin Sandbox](https://bitcoin-sandbox.vercel.app/) · [Source](https://github.com/greyw0rks/bitcoin-sandbox)

Each learner gets Alpha and Beta Bitcoin Core wallets. The lab shows real UTXOs, transaction previews, explicit broadcast review, a transaction explorer and three guided experiments. Settings and learning records persist, and uncertain broadcasts can be checked against the original transaction.

Every lab transaction uses regtest coins with no monetary value. The hosted lab uses Convex for owner-bound records and a trusted private Bitcoin Core runner. The demonstration runner requires the builder's computer to remain online.

Run the complete local lab on Linux x64 with Node.js 22.12+ and pnpm:

```sh
./start.sh
```

Open http://127.0.0.1:4404.

Bitcoin Sandbox has its own repository, public site and submission. The release builds only its interface. Retained evidence records builder-controlled protocol tests; independent learner outcomes are unmeasured.

Read the [product guide](docs/sandbox/README.md), [setup](docs/sandbox/SETUP.md), [security notes](docs/sandbox/SECURITY.md) and [demo outline](docs/sandbox/DEMO.md).
