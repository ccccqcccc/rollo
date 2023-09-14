# rollo

Set up a blockchain node on your local PC.

## bitcoin

To reduce computer load, limit memory usage and number of peer connections, and start as a pruning node

docker image: `ruimarinho/bitcoin-core:latest`

## ethereum

Start as a [light client](https://geth.ethereum.org/docs/fundamentals/les) to reduce the load on your computer.

docker image: `ethereum/client-go`

NOTE: Note: The light client does not currently work with POS.
