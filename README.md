# festival-coin-official

Creating simplewallet addresses


$ ./simplewallet --config-file configs/festival.conf --generate-new-wallet MY.wallet --password PASSWORD

config path exist
forknote wallet v1.0.9.1.662()
Sync from timestamp: 1455950318
Error: wallet failed to connect to daemon (http://localhost:29081).
Generated new wallet: D9CTMkRfsJ594cuvX2pGXNWMFK5ARwxPN1x7bFC5wY5XTZxf12LjWUK5QkMVeSkD6gT532FepdaohRYkt99e9gdF6hyrUgx
view key: f45a0505d89e4c3bbb91c3481861c12b2b0c6e43b9de23fa108a48a0db116901
**********************************************************************
Your wallet has been generated.
Use "help" command to see the list of available commands.
Always use "exit" command when closing simplewallet to save
current session's state. Otherwise, you will possibly need to synchronize
your wallet again. Your wallet key is NOT under risk anyway.
**********************************************************************


Starting Mining

To start mining:

$ ./miner --daemon-address 127.0.0.1:3949  --address [WALLET_ADDRESS]

Examples :
$ ./miner --daemon-address 127.0.0.1:3949  --address D6WLtrV1SBWV8HWQzQv8uuYuGy3uwZ8ah5iT5HovSqhTKMauquoTsKP8RBJzVqVesX87poYWQgkGWB4

Notice: The first few blocks may take a few hours to be found

Connecting the daemon to a blockchain
To connect to the daemon to existing blockchain, just start forknoted with the corresponding configuration file.

$ ./forknoted --config-file configs/festival.conf



To start simplewallet:

$ ./simplewallet --config-file configs/festival.conf

Mining with miner
miner needs a running and synced daemon.

http://forknote.net/documentation/





