# Lineth

[![CI](https://github.com/LFDT-lineth/linea-monorepo/actions/workflows/main.yml/badge.svg)](https://github.com/LFDT-lineth/linea-monorepo/actions/workflows/main.yml)
[![CodeQL](https://github.com/LFDT-lineth/linea-monorepo/actions/workflows/codeql.yml/badge.svg)](https://github.com/LFDT-lineth/linea-monorepo/actions/workflows/codeql.yml)
[![Codecov](https://codecov.io/gh/LFDT-lineth/linea-monorepo/graph/badge.svg?token=2TM55P0CGJ)](https://codecov.io/gh/LFDT-lineth/linea-monorepo)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/LFDT-lineth/linea-monorepo/blob/main/LICENSE-APACHE)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/LFDT-lineth/linea-monorepo/blob/main/LICENSE-MIT)
[![Discord](https://img.shields.io/discord/905194001349627914?logo=Hyperledger&style=plastic)](https://discord.com/invite/hyperledger)
[![X Follow](https://img.shields.io/twitter/follow/LineaBuild?style=social)](https://x.com/LineaBuild)

Lineth is the open-source software stack powering [Linea](https://linea.build), a developer-ready Layer 2 network scaling Ethereum, secured by a zero-knowledge rollup built on lattice-based cryptography. The stack is open source under the [Apache 2.0][Apache License] and [MIT][MIT License] licenses.

Lineth is built around [Besu](https://github.com/besu-eth/besu) as its reference execution client, with additional support for [Reth](https://github.com/paradigmxyz/reth), [Nethermind](https://github.com/NethermindEth/nethermind), and [Erigon](https://github.com/erigontech/erigon). To run a full node, an execution client is paired with the consensus client [Maru](https://github.com/Consensys/maru).

## Useful Links

* [Linea Documentation](https://docs.linea.build)
* [Lineth Issues][Lineth Issues]
* [How to Contribute to Lineth](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/contribute.md)
* [Get Started Guide](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/get-started.md)
* [Local Development Guide](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/local-development-guide.md)
* [Linea Blog](https://linea.mirror.xyz)
* [Support](https://support.linea.build)

## Looking for the Lineth code?

The Lineth stack is split across several repositories:

* [linea-monorepo](https://github.com/LFDT-lineth/linea-monorepo) — main repository for the Lineth stack (smart contracts, prover, coordinator, postman, Linea-Besu plugins)
* [zkc](https://github.com/LFDT-lineth/zkc) — zk constraint compiler
* [doc.linea](https://github.com/Consensys/doc.linea) — source for the Linea documentation site at [docs.linea.build](https://docs.linea.build)

## Issues

Lineth issues are tracked [in the GitHub issues tab][Lineth Issues]. See the [contribution guide](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/contribute.md) for details on searching and filing issues.

If you have questions or comments, find us on the [LFDT Discord server](https://discord.com/invite/hyperledger) in the dedicated Lineth channels:

* [#linea-announcements](https://discord.com/channels/905194001349627914/1499425506439729262) — releases and project announcements
* [#lineth-general](https://discord.com/channels/905194001349627914/1498775958080065746) — general discussion
* [#lineth-dev](https://discord.com/channels/905194001349627914/1499425447539380224) — development and contributor chat

## For Users

* [Linea website](https://linea.build)
* [Bridge tokens](https://docs.linea.build/developers/guides/bridge)
* [Deploy a smart contract](https://docs.linea.build/developers/quickstart/deploy-smart-contract)
* [Run a node](https://docs.linea.build/developers/guides/run-a-node)

## For Developers

* [Contributing Guidelines](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/contribute.md)
* [Code of Conduct](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/code-of-conduct.md)
* [Security Policy](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/security.md)
* [Linea Documentation](https://docs.linea.build) for running and using Linea

### Development

Instructions for getting started with the Lineth codebase:

* [Local Development Guide](https://github.com/LFDT-lineth/linea-monorepo/blob/main/docs/local-development-guide.md)
* [Code Coverage](https://codecov.io/gh/LFDT-lineth/linea-monorepo)
* [Continuous Integration](https://github.com/LFDT-lineth/linea-monorepo/actions)

For Besu:Lineth related contributions, see the [Besu contribution guide](https://lf-hyperledger.atlassian.net/wiki/spaces/BESU/pages/22156850/How+to+Contribute).

## Agent Documentation

For AI coding agents and developer tools:

* Canonical instructions: [AGENTS.md](https://github.com/LFDT-lineth/linea-monorepo/blob/main/AGENTS.md)
* Claude Code entry point: [CLAUDE.md](https://github.com/LFDT-lineth/linea-monorepo/blob/main/CLAUDE.md)
* GitHub Copilot entry point: [.github/copilot-instructions.md](https://github.com/LFDT-lineth/linea-monorepo/blob/main/.github/copilot-instructions.md)

[Lineth Issues]: https://github.com/LFDT-lineth/linea-monorepo/issues
[Apache License]: https://github.com/LFDT-lineth/linea-monorepo/blob/main/LICENSE-APACHE
[MIT License]: https://github.com/LFDT-lineth/linea-monorepo/blob/main/LICENSE-MIT
