# ETHLocal

ETHLocal is aimed to build a local private Ethereum Network by docker container.

## Network Architecture
- Bootnode: listens on porn 30303, is used for peer discovery purpose.
- JSON-RPC endpoint: this node exposes JSON-RPC API over HTTP endpoint on port 8545. 
- Minernode: this node is responsible for mining (the process of creating a new block in our blockchain).

## Build and Run

```
cd network
docker-compose up -d
```



### Reference
https://medium.com/scb-digital/running-a-private-ethereum-blockchain-using-docker-589c8e6a4fe8