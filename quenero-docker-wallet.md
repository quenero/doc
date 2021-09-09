## Quenero docker

Run Quenero by using docker

```shell
docker pull quenero/quenero:latest
```

Then run it like this

```shell
docker run --rm -it quenero/quenero 
```

If you want to run with Masternode
```shell
docker run --rm -it quenero/quenero --masternode --storage-server-port 33231 --masternode-public-ip 181.14.32.84
```

create a wallet with docker
Get the docker container id by running the below code
```css
docker ps 
```
This will output something like the below 
```css
CONTAINER ID   IMAGE             COMMAND                  CREATED        STATUS        PORTS             NAMES
3217ed3020b   quenero/quenero   "quenerod --p2p-bind…"   11 hours 
```
Then run the below code to create wallet
```css
docker exec -it 3217ed3020b bash
```

run the below
```css
cd /wallet
```
run the below
```css
quenero-wallet-cli
```
