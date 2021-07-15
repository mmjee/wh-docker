### Docker-Compose set up for Warehouse

#### How To Use

```shell
git clone --recurse-submodules --depth 1 https://github.com/mmjee/wh-docker.git
$EDITOR docker-compose.yml
$EDITOR redis.conf
docker-compose up -d
docker-compose logs -f
```

#### Warning

Please do change the MongoDB & Redis default password.
