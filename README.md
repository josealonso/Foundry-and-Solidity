# Foundry-and-Solidity
Learning intermediate Solidity concepts using Foundry (no more Hardhat)

## Installing Foundry

```bash
curl -L https://foundry.paradigm.xyz | bash
```

then 

```bash
foundryup
```

installs  install the complete Foundry suite 
- **forge**
- **cast**
- **anvil**
- **chisel**

```bash
$ forge --version
```

> forge Version: 1.7.1
  Commit SHA: 4072e48705af9d93e3c0f6e29e93b5e9a40caed8
  Build Timestamp: 2026-05-08T07:50:55.527285345Z (1778226655) 
  Build Profile: dist

```bash
$ forge compile
```

compiles the Solidity file and place the generated EVM bytecode in the `out` directory.

### Using Anvil 
- Run `anvil`, the Foundry local node.
- Type
  `forge create SimpleStorage --rpc-url http://127.0.0.1:8545 --private-key 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80` or
  `forge create SimpleStorage --interactive`
  
