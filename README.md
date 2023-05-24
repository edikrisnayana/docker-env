# local-env
Local environment using Docker for backend testing locally

## Prerequisites
1. install [Docker](https://docs.docker.com/get-docker/)
2. install [Docker Compose](https://docs.docker.com/compose/install/)
3. install [Docker configured as non-root user](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)

## How to Run
```sh
docker-compose up
```

## How to Connect with CLI
### Mongo
- install mongo cli
  ```sh
  sudo apt install mongodb-mongosh
  ```
- connect to mongo using mongo cli
  ```sh
  mongosh --host 192.168.200.2 --port 27017
  ```

### Redis
- install redis cli
  ```sh
  sudo apt install redis-tools
  ```
- connect to redis using redis cli
  ```sh
  redis-cli -h 192.168.200.3 -p 6379
  ```

### Postgresql
- install postgresql cli
  ```sh
  sudo apt install postgresql-client
  ```
- connect to postgresql using postgresql cli
  ```sh
  psql -h 192.168.200.4 -p 5432 -U postgres
  ```