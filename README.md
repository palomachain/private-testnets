# private-testnets
Private Testnet Documentation

Instructions and validator information for running Paloma private testnets. Each testnet has its data preserved from the time of its execution in its directory.

2022-05-20 - [20220520 testnet](./20220520)

The following describes what is requried for a single VM that will act as a validator in a `paloma` testnet.

## VM Requirements

1. Compute: 2 CPU
2. RAM: 16 GB (MINIMUM)
3. Disk: 50GB-100GB
3. Open Ports:
- 26656 (tendermint p2p)
- 26657 (tendermint rpc)
- 9090  (tendermint grpc)
- 1317  (cosmos-sdk api)
- 30303 (geth p2p)
