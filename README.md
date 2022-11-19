# Redis

This repository contains some essential files that can be used for deploy the Redis container (standalone mode).

## Preparations

Edit the iten below in docker-compose.yml file:

```yml
...
...
command: redis-server --requirepass STRONGER_PASSWORD #put a strong password here
...
...
```

## Deploy

To deploy the container, just follow the command below:

```shell
docker compose up -d
```