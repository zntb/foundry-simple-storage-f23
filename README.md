# Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

## ZkSync Documentation

Clone the zksync repo:

```bash
git clone git@github.com:matter-labs/foundry-zksync.git
```

Go to cloned repository folder:

```bash
cd foundry-zksync
```

Run the Installer:

```bash
./install-foundry-zksync
```

Kill the terminal and start a new terminal session from the project folder.

Verify the Installation:

```bash
forge --version
```

Run foundryup in zksync:

```bash
foundryup-zksync
```

Build commands help file:

```bash
forge build --help
```

Switch back to vanilla foundry:

```bash
foundryup
```

<hr>

https://book.getfoundry.sh/

## Usage

### Init a new project

```shell
$ forge init
```

### Basic foundry commands

```shell
cast
forge
anvil
```

### Build

```shell
$ forge build
```

### Build in ZkSync

```shell
$ forge build --zksync
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
