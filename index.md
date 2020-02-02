## About Lero

Lero is a decentralized peer-to-peer exchange network and stable exchange medium, borned as private Internet money that respects and protects privacy.

Lero would be the fastest cryptocurrency in the future.

### Specification
Ticker: Lero

Symbol: LO.

Proof-of-work algorithm: CryptoNight

Block time: 240 seconds

Difficulty: retarget each block

Block reward: 
slight decrease every block according to formula:
BaseReward = (MSupply - A)/218

where MSupply is the number of atomic units and 'A' is amount of already generated coins

Divisible up to: 1012 atomic units (up to 12 decimal places)

Emission: infinite, initial supply – 10 billion lero.

Tail emission: ~2% of initial supply per year, minimal block reward: 10 Lero.


### Release History
Coming Soon

## Get to Startd

###Getting Started
Let’s walk through core Lero concepts as we tackle a simple use case.

###Connecting the daemon to a blockchain

To connect to the daemon to existing blockchain, just start forknoted with the corresponding configuration file.


####For Mas OS and Linux
$ ./lerod  --rpc-bind-ip=0.0.0.0 --rpc-bind-port=12848 

Using _./lerod --help_  to   Produce help message
                            

####For Windows
$ lerod  --rpc-bind-ip=0.0.0.0 --rpc-bind-port=12848 

Using _lerod --help_  to   Produce help message

###Starting simplewallet
To start simplewallet:

####For Mas OS and Linux
$ ./simplewallet 

Using _./simplewallet --help_  to   Produce help message

####For Windows
$ simplewallet 

Using _simplewallet --help_  to   Produce help message

###Mining with miner
miner needs a running and synced daemon.

**Note： Using _--help_  to   Produce help message**


_To start mining_:

####For Mas OS and Linux
$ ./miner --daemon-address 127.0.0.1:[DAEMON_RPC_PORT]  --address [WALLET_ADDRESS]

_Examples_

Starting miner :

$ ./miner --daemon-address 127.0.0.1:12848--address 

####For Windows
$ miner --daemon-address 127.0.0.1:[DAEMON_RPC_PORT]  --address [WALLET_ADDRESS]

_Examples_

Starting miner :

$ miner --daemon-address 127.0.0.1:12848--address 

## Announcements

Lero is Free to used.


## Support 
Submit issue to github.

