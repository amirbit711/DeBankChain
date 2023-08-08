# DeBankChain - DeBank layer 2 solution

The DeBankChain is the Layer 2 scaling solution powered by [bedrock version](https://community.optimism.io/docs/developers/bedrock/) of Optimism OP Stack.


## Features

Besides the [differentiators of bedrock](https://community.optimism.io/docs/developers/bedrock/differences/), DeBankChain is the solution that we aim to provide the better optimistic rollup solution.

### Node optimization

- Batch block submitting
- Optimized block verification bettwen layer 1 and layer 2
- Customized trancaction type
- Block time is 2 seconds

### JSONRPC-API enhancement

- EVM Pre Execution
- EVM Transaction Tracing
- Multicall


## Documentation

If you want to build on top of DeBankChain, refer to the [DeBankChain Doc](https://github.com/DeBankDeFi/DeBankChain/tree/main/docs/build).

## Community

To get help from other developers, discuss ideas, and stay up-to-date on what's happening, become a part of our community on Telegram. Join our [official Telegram Channel](https://t.me/DeBankEN).

## Directory Structure

<pre>
~ DeBankChain ~~
├── <a href="./packages">packages</a>
│   └── <a href="./packages/contracts-bedrock">contracts-bedrock</a>: Bedrock smart contracts.
├── <a href="./op-bindings">op-bindings</a>: Go bindings for Bedrock smart contracts.
├── <a href="./op-batcher">op-batcher</a>: L2-Batch Submitter, submits bundles of batches to L1
├── <a href="./op-e2e">op-e2e</a>: End-to-End testing of all bedrock components in Go
├── <a href="./op-node">op-node</a>: rollup consensus-layer client.
├── <a href="./op-proposer">op-proposer</a>: L2-Output Submitter, submits proposals to L1
├── <a href="./ops-bedrock">ops-bedrock</a>: Bedrock devnet work
└── <a href="./specs">specs</a>: Specs of the rollup starting at the Bedrock upgrade
</pre>

## License

All files within this repository are licensed under the [MIT License](https://github.com/DeBankDeFi/DeBankChain/blob/main/LICENSE) unless stated otherwise.
