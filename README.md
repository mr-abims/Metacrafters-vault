# Metacrafters- Vault 
Deploying and interacting with contracts on a local subnet

## Subnet

```shell
$ avalanche subnet create ASubnet 
```
```shell
$ avalanche subnet deploy  ASubnet 
```




### Smart contract 

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
$ forge script script/Token.s.sol:TokenScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```