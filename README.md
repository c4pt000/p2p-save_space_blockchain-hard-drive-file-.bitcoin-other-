# p2p-save_space_blockchain-hard-drive-file-.bitcoin-other-

instead of downloading the blockchain data locally to the drive

use a p2p model of socket to socket file i/o with a local cache of 300-500mb

with a starting point of the genesis block, a snapshot block height and the current point with the snapshot blockheight adjusting to keep the cache low of the local file to less than 500mb or 300mb

using p2p sockets for i/o write/read operations from connected peer to peer using "sockets with i/o rw" via standard port open pathways in the network TCP
