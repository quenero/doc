---
description: >-
  Deregister Your Quenero Masternode
---


Follow this easy steps to deregister your Masternode 

- Run the quenero `quenero-wallet-cli` or `quenero-wallet-cli.exe` and and enter the below command

```text
request_stake_unlock <masternode_pubkey>

```

Once you do that it will take at least 10950 blocks and the quenero for masternode will then become unlocked.

This will removes your Masternode from the quenero network, and your quenero become locked and unspendable for at most 21600 blocks 

from the block in which your masternode was deregistered.

Once a deregistration of your Masternode is received, it overrides the 10950 block stake unlock time, and sets the unlock time to at least 21600 blocks


Check your locked stakes information with the below command from your quenero `quenero-wallet-cli` or `quenero-wallet-cli.exe` console wallet

```text

print_locked_stakes

```


If you combined to setup your `Masternode` it will deregister once you apply for it to be unlock
