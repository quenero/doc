---
description: >-
  Setup Quenero Docker Wallet
---


Run Quenero by using docker

```text
docker pull quenero/quenero:latest
```

Then run it like this

```text
docker run --rm -it quenero/quenero 
```

If you want to run with Masternode
```text
docker run --rm -it quenero/quenero --masternode --storage-server-port 33231 --masternode-public-ip 181.14.32.84
```

## Create a wallet with docker
Get the docker container id by running the below code

```text
docker ps 
```
This will output something like the below 
```text
CONTAINER ID   IMAGE             COMMAND                  CREATED        STATUS        PORTS             NAMES
3217ed3020b   quenero/quenero   "quenerod --p2p-bind…"   11 hours 
```
Then run the below code to create wallet

```text
docker exec -it 3217ed3020b bash
```

run the below

```text
cd /wallet
```
run the below

```text
quenero-wallet-cli
```
