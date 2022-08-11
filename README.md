# local-env
Local environment using Docker

## Prerequisites
1. [Docker](https://docs.docker.com/get-docker/)
2. [Docker Compose](https://docs.docker.com/compose/install/)
3. [Docker configured as non-root user](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)

## How to Run
```sh
docker-compose up
```

## How to Connect with CLI
### Mongo
```sh
mongo <host>:<port>
```

### Redis
```sh
redis-cli -h <host> -p <port>
```