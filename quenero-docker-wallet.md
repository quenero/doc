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
