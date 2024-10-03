# UTXOxEVM-v0.2 Repository Overview

Welcome to the UTXOxEVM-v0.2 repository-proposal for the UTXO Network. This repository serves as a central hub for transgression of integrating the UTXO blockchain model with Ethereum Virtual Machine (EVM) capabilities and Akropolis current environment. It houses a collection of submodules that are critical for the process.

It's worth noting that Kaon's full codebase extends well beyond what is visible here. In total, Kaon encompasses over 1,000,000 lines of code, with approximately 17% of this being open-source and publicly accessible. This repository showcases key components of the project while maintaining the integrity and security of proprietary elements.

## Repository Structure

The UTXOxEVM-v0.2 repository includes the following submodules, each with a specific function within the project's ecosystem:

### Common Libraries
- rust-network: A fork of rust-bitcoin adapted for the our Network. [GitHub Repository](https://github.com/akropolisio/rust-kaon)
- rust-kaon-rpc: RPC interfaces for rust-network. [GitHub Repository](https://github.com/akropolisio/rust-kaon-rpc)
- EthRPCGate: A transformer for converting RPC data formats from Bitcoin to Ethereum. [GitHub Repository](https://github.com/akropolisio/EthRPCGate)

### JavaScript Ethereum Libraries
- ethereumjs-monorepo: A fork of EthereumJS with adaptations for the our Network. [GitHub Repository](https://github.com/akropolisio/ethereumjs-monorepo)
- ethers.js: A fork of ethers.js configured for the our Network. [GitHub Repository](https://github.com/akropolisio/ethers.js)

### JavaScript Uniswap Libraries
- portis-web-sdk: UniSwap V2 web SDK customized for our Network parameters and addresses. [GitHub Repository](https://github.com/akropolisio/portis-web-sdk)
- uniswap-sdks: SDKs from UniSwap, modified for our Network. [GitHub Repository](https://github.com/akropolisio/uniswap-sdks)
- v2-sdk: SDK from UniSwap V2 integrated with our Network parameters. [GitHub Repository](https://github.com/akropolisio/v2-sdk)
- web3-react: Adapted from UniSwap V2 for use with our Network parameters. [GitHub Repository](https://github.com/akropolisio/web3-react)
- v2-periphery: Periphery libraries from UniSwap V2 tailored for the our Network. [GitHub Repository](https://github.com/akropolisio/v2-periphery)

### Ordinals API
- chainhook: Provides basic search/filter operations API from the chain in Bitcoin format. [GitHub Repository](https://github.com/akropolisio/chainhook)
- ordhook: Manages hooks operation from the chain in Bitcoin format. [GitHub Repository](https://github.com/akropolisio/ordhook)
- ordinals-api: Manages Inscriptions operations from the chain in Bitcoin format. [GitHub Repository](https://github.com/akropolisio/ordinals-api)

### Blockscout Scanner
- blockscout-backend: The current Blockscout fetcher deployed on our. [GitHub Repository](https://github.com/akropolisio/blockscout-backend)
- blockscout-frontend: The web frontend for the Blockscout explorer, available at [explorer.testnet.kaon.one](https://explorer.testnet.kaon.one). [GitHub Repository](https://github.com/akropolisio/blockscout-frontend)

## Contribution

Contributions to the UTXOxEVM-v0.2 repository are welcome. Please refer to each submodule's specific repository for contribution guidelines and issue tracking.

## License

Each submodule in the UTXOxEVM-v0.2 repository may be covered under different licenses. Please refer to the individual repositories for detailed licensing information.

Thank you for visiting the UTXOxEVM-v0.2 repository of the project. Here you can grasp a bit of what will be in a future.
