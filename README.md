# Foundary-DEFI-StableCoin Project

Welcome to the Foundary-DEFI-StableCoin Project! This repository contains the Solidity code for building a decentralized stablecoin system on the Ethereum blockchain. Leveraging Foundry for development, testing, and deployment, this project is designed to provide a secure, efficient, and scalable solution for decentralized finance (DeFi) enthusiasts.

## Key Features
- **Decentralized Stablecoin**: A stable cryptocurrency pegged to a USD value, designed to minimize volatility.
- **Collateralized Minting**: Users can mint stablecoins by locking collateral in smart contracts.
- **Liquidation Mechanism**: Automated liquidation ensures that the system remains solvent and over-collateralized.
- **Gas Efficiency**: Optimized for reduced transaction costs while maintaining robust security.
- **Scalability**: Built with modular architecture for seamless integration with other DeFi protocols.

## Project Structure
- **Contracts**: Contains Solidity files for the stablecoin, collateral management, and liquidation mechanisms.
- **Scripts**: Scripts for deploying and interacting with the smart contracts on Ethereum testnets and mainnet.
- **Tests**: Comprehensive unit and invariant tests to validate contract functionality and security.

## Getting Started

### Prerequisites
- **Foundry**: Ensure Foundry is installed. If not, install it by running:
   ```bash
   curl -L https://foundry.paradigm.xyz | bash
   foundryup

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jprabhat/Foundary-DEFI-StableCoin.git
   cd Foundary-DEFI-StableCoin

2. **Run Project**:
    ```bash
    make install
    make build
    make test
3. **.env Configuration**:
      SEPOLIA_RPC_URL=< Your URL >
      ETHERSCAN_API_KEY=< Your Etherscan API Key >
      PRIVATE_KEY=0x< Your Private Key >



Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
