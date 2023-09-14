# rollo

Set up a blockchain node on your local PC.

## containers

### bitcoin

`ruimarinho/bitcoin-core`

To reduce computer load, limit memory usage and number of peer connections, and start as a pruning node.

### ethereum

`ethereum/client-go`

Start as a [light client](https://geth.ethereum.org/docs/fundamentals/les) to reduce the load on your computer.

NOTE: Note: The light client does not currently work with POS.
