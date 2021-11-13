# p2p-save_space_blockchain-hard-drive-file-.bitcoin-other-

instead of downloading the blockchain data locally to the drive ( AS A GIGANTIC DATASTORE of 250GB)

use a p2p model of socket to socket file i/o with a local cache of 300-500mb

with a starting point of the genesis block, a snapshot block height and the current point with the snapshot blockheight adjusting to keep the cache low of the local file to less than 500mb or 300mb

and an initial point has to be kept from snapshot of the genesis block for 50mb to 100mb and the initial point of the blockchain snapshot recently starting point

the snapshot of the height of the blockchain minus 20,000 blocks keeps adjusting to the cache level size

using p2p sockets for i/o write/read operations from connected peer to peer using "sockets with i/o rw" via standard port open pathways in the network TCP
