# Kotti
[![Join the chat at https://gitter.im/goerli/kotti](https://badges.gitter.im/goerli/kotti.svg)](https://gitter.im/goerli/kotti?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<center>
  <h3 align="center">Kotti</h3>
  <p align="center">
    An Ethereum Classic PoW testnet to replace Morden Classic.
    <br />
    <a href="https://blockscout.com/etc/kotti/">Explorer</a>
    ·
    <a href="https://kotti.dash.fault.dev/">Dashboard</a>
    ·
    <a href="https://kotti.fork.fault.dev/">Fork Mon</a>
    ·
    <a href="http://kottifaucet.me/">Faucet</a>
    ·
    <a href="https://github.com/eth-classic/kotti/issues/new">Create an Issue</a>
  </p>
</center>

_Launch: December, 2018 by the Goerli Initiative. Read more: https://github.com/goerli/testnet_

- Network ID: `6`
- Chain ID: `6`
- Frontier: `0`
- Homestead: `0`
- GasReprice: `0`
- Diehard: `0`
- Gotham: `0`
- Defuse Difficulty Bomb: `0`
- Atlantis: `716_617`
- Agharta: `1_705_549`
- Phoenix: `2_200_013`
- ~~Thanos~~: `N/A` (not applicable for clique)

### Genesis hash

```
0x14c2283285a88fe5fce9bf5c573ab03d6616695d717b12a127188bcacfc743c4
```

### Resources

Status Dashboard:
- https://kotti.dash.fault.dev

Fork Monitoring:
- https://kotti.fork.fault.dev

Block Explorer:
- https://blockscout.com/etc/kotti
- https://expedition.dev/?network=kotti

Faucets:
- http://kottifaucet.me/

Public End Points:
- https://www.ethercluster.com/kotti
- https://services.fault.dev

### Core-Geth

Minimum required version: `v1.11.0`

```
geth --kotti
```
- https://github.com/etclabscore/core-geth/releases

### Hyperledger Besu

Minimum required version: `v1.4.1`

```
besu --network kotti
```
- https://github.com/hyperledger/besu/releases

### Nethermind (experimental)

Minimum required version: `v1.8.92`

```
./Nethermind.Runner --config kotti 
```
download nethermind, inflate and then copy the nethermind.cfg into the config-subdirectory of nethermind 
as well as the nethermind.json needs to be copied into the chainspec-subdirectory within the inflated nethermind-root-directory.
if errors occur and ubuntu/debian is the env, then 
```sudo apt-get update && sudo apt-get install libsnappy-dev libc6-dev libc6 unzip``` 
will help.

- https://github.com/NethermindEth/nethermind/releases

### Open ETC (deprecated, formerly Open Ethereum, Parity Ethereum)

Minimum required version: `v3.0.1`

```
openetc --chain kotti
```
- https://github.com/openetc/openetc/releases
