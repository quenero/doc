### Solo Mining Quenero 

Mining Quenero is very easy and without stress. We are looking to setup a pool but for now you can simply solo mine

Download he QMR console wallet from [https://quenero.tech/wallet/quenero-linux-x64-v10.1.0.tar.bz2](https://quenero.tech/wallet/quenero-linux-x64-v10.1.0.tar.bz2)

### untar the wallet
tar -vf quenero-linux-x64-v10.1.0.tar.bz2

cd quenero


You will see the following for linux
``shell
quenero-blockchain-ancestry
quenero-blockchain-depth
quenero-blockchain-export
quenero-blockchain-import
quenero-blockchain-mark-spent-outputs
quenero-blockchain-stats
quenero-blockchain-usage
quenero-gen-trusted-multisig
quenero-sn-keys
quenero-wallet-cli
quenero-wallet-rpc
quenerod
```
And the following for window

```shell
quenero-blockchain-export.exe
quenero-blockchain-import.exe
quenero-blockchain-mark-spent-outputs.exe
quenero-blockchain-stats.exe
quenero-blockchain-usage.exe
quenero-gen-trusted-multisig.exe
quenero-sn-keys.exe
quenero-wallet-cli.exe
quenero-wallet-rpc.exe
quenerod.exe
```

Run the Daemon Wallet

Run it like this assuming we downloaded it in download folder and open it in power shell terminal if using window

```shell
C:\Users\USER\Downloads\quenero-win-x64-v10.1.0\quenero>./quenerod.exe
```

You will see something like this:

```
C:\Users\USER\Documents\Downloads\quenero-win-x64-v10.1.0\quenero> ./quenerod.exe
2021-09-06 23:36:33.045 I Quenero 'Beautiful Girls' (v10.1.0-release)
2021-09-06 23:36:33.048 I Initializing daemon objects...
2021-09-06 23:36:33.049 I - cryptonote protocol
2021-09-06 23:36:33.049 I - p2p
2021-09-06 23:36:33.058 I - admin HTTP RPC server
2021-09-06 23:36:33.074 I Done daemon object initialization
2021-09-06 23:36:33.078 I Starting up quenerod services...
2021-09-06 23:36:33.079 I Starting core
2021-09-06 23:36:33.080 I x25519 public key: ae38e233421e95314033938e1e5d170d51ae33d7bf1aa8d234e5fec234
2021-09-06 23:36:33.081 I Loading blockchain from folder "C:\\ProgramData\\quenero\\lmdb" ...
2021-09-06 23:36:33.120 I Starting queneromq
2021-09-06 23:36:33.326 I Masternode data loaded successfully, height: 5030
2021-09-06 23:36:33.327 I 2 nodes and 63 recent states loaded, 0 historical states loaded, (7.97 kB)
2021-09-06 23:36:33.327 I Loading blocks into quenero subsystems, scanning blockchain from height: 5031 to: 5327 (snl: 5031, ons: 5327)
2021-09-06 23:36:33.398 I Done recalculating quenero subsystems (0.0451162s) (snl: 0s; ons: 0s)
2021-09-06 23:36:33.400 I Loading checkpoints
2021-09-06 23:36:33.401 I Starting QueneroMQ
2021-09-06 23:36:33.410 I Starting admin HTTP RPC server
2021-09-06 23:36:33.412 I Starting command-line processor
2021-09-06 23:36:33.420 I Starting up main network
2021-09-06 23:36:34.429 I
**********************************************************************
The daemon will start synchronizing with the network. This may take a long time to complete.

You can set the level of process detailization through "set_log <level|categories>" command,
where <level> is between 0 (no details) and 4 (very verbose), or custom category based levels (eg, *:WARNING).

Use the "help" command to see the list of available commands.
Use "help <command>" to see a command's documentation.
**********************************************************************
2021-09-06 23:36:40.812 I Synced 5378/5378
2021-09-06 23:36:40.813 I SYNCHRONIZED OK
2021-09-06 23:36:40.813 I Synced 51 blocks in 4 seconds (12.75 blocks per second)
2021-09-06 23:36:40.814 I
**********************************************************************
You are now synchronized with the network. You may now start quenero-wallet-cli.

Use the "help" command to see the list of available commands.
**********************************************************************
2021-09-06 23:36:40.815 I SYNCHRONIZED OK
```
Open another terminal and go to he directory were you have the wallet and look for #quenero-wallet-cli.exe

```shell

C:\Users\USER\Downloads\quenero-win-x64-v10.1.0\quenero> ./quenero-wallet-cli.exe
This is the command line Quenero wallet. It needs to connect to a Quenero
daemon to work correctly.

WARNING: Do not reuse your Quenero keys on a contentious fork, doing so will harm your privacy.
 Only consider reusing your key on a contentious fork if the fork has key reuse mitigations built in.

Quenero 'Beautiful Girls' (v10.1.0-release)
Logging to C:\Users\USER\Documents\Downloads\quenero-win-x64-v10.1.0\quenero\quenero-wallet-cli.log
Specify wallet file name (e.g., MyWallet). If the wallet doesn't exist, it will be created.
Wallet file name (or Ctrl-C to quit):
```
Enter and name in 'Wallet file name (or Ctrl-C to quit):', let say jack is the name
```shell 
Wallet file name (or Ctrl-C to quit): jack
```
Better follow the prompt

```shell
Quenero 'Beautiful Girls' (v10.1.0-release)
Logging to C:\Users\USER\Downloads\quenero-win-x64-v10.1.0\quenero\quenero-wallet-cli.log
Specify wallet file name (e.g., MyWallet). If the wallet doesn't exist, it will be created.
Wallet file name (or Ctrl-C to quit): jack
No wallet found with that name. Confirm creation of new wallet named: "jack" (Y/Yes/N/No): y
Generating new wallet...
Enter a new password for the wallet:
Confirm password:
List of available languages for your wallet's seed:
If your display freezes, exit blind with ^C, then run again with --use-english-language-names
0 : Deutsch
1 : English
2 : EspaA±ol
3 : FranA§ais
4 : Italiano
5 : Nederlands
6 : PortuguAªs
7 : Ñ?ÑƒÑ?Ñ?DºD,D1 Ñ?D·Ñ<Dº
8 : æ-¥æo¬èªz
9 : çr?ä½"ä,-æ-╪ (ä,-å>½)
10 : Esperanto
11 : Lojban
Enter the number corresponding to the language of your choice: 1
Generated new wallet: 44pnUJYGh3YbeHR6sheWtGV3Bvu5EWNLVhDPAR82wNMM2mWzwarsv2iUn8pNMp38USJM2jtWvwYs1H1XFuviWQmBAxQhU7z
View key: 983e8e73e56a4894000e310b2983a47663a43e2198a65e738i993
**********************************************************************
Your wallet has been generated!
To start synchronizing with the daemon, use the "refresh" command.
Use the "help" command to see the list of available commands.
Use "help <command>" to see a command's documentation.
Always use the "exit" command when closing quenero-wallet-cli to save
your current session's state. Otherwise, you might need to synchronize
your wallet again (your wallet keys are NOT at risk in any case).

NOTE: the following 25 words can be used to recover access to your wallet. Write them down and store them somewhere safe and secure. Please do not store them in your email or on file storage services outside of your immediate control.

Warning: NEVER give your Quenero wallet seed to ANYONE else. NEVER input your Quenero wallet seed into any software or website other than the OFFICIAL Quenero CLI or GUI wallets, downloaded directly from the Quenero GitHub (https://github.com/quenero/) or compiled from source.
Are you sure you want to access your wallet seed? (Y/Yes/N/No):yes

ball air knife often textbook fiat eternal base
family playing chair school test dab perfect serving
pouch era when eject dad coming plan prying skill
**********************************************************************
If you are new to Quenero, type "welcome" for a brief overview.
Starting refresh...
Refresh done, blocks received: 7
Untagged accounts:
          Account               Balance      Unlocked balance                 Label
 *       0 44pnUJ           0.000000000           0.000000000       Primary account
----------------------------------------------------------------------------------
          Total           0.000000000           0.000000000
Currently selected account: [0] Primary account
Tag: (No tag assigned)
Balance: 0.000000000, unlocked balance: 0.000000000
Background refresh thread started
[wallet 44pnUJ]:
```

Once the wallet is created as above, use the below code to start mining in solo mode

```shell
start_mining
```
