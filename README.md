## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

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
you can see all opcodes in here ths website 
https://www.evm.codes/
https://www.ethervm.io/

in terminal you can try and test this 
cast to-base 0x60 dec
cast to-base 0x60 bin``
after .huff v1 file after that run this code than you get 
-huffc src/horse
StoreV1/HorseStore.huff --bin-runtime
5f3560e01c8063cdfead2e1461001b578063e026c01714610022575b6004355f55005b5f545f5260205ff3
-you can paste this in evm.code/playground in bytecode than you get proper result
-first PUSH4 code in down side than run than this work proper


after adding in test need to install huff
-forge install huff-language/foundry-huff --no-commit


-forge test --match-path *Huff* --debug testReadValue -vvvv

-Decompilers
**Dedaub **https://app.dedaub.com/ethereum/address/0x6b175474e89094c44da98b954eedeac495271d0f/decompiled
**Heimdall ** https://github.com/Jon-Becker/heimdall-rs