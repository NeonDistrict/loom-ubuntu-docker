# Loom Docker Helper

This project is for providing a sterile environment with the latest running version of Loom. We're using Ubuntu 16.04, which is one of the more recent supported LTS versions of Ubuntu Linux.

The Dockerfile contents are largely provided by https://loomx.io/developers/docs/en/prereqs-ubuntu.html.


# Using Docker

## Ways to debug:
```
docker logs [container]
```

## Build
```
docker build -t loom-ubuntu-docker .
```

## Run & Stop: Using Docker Compose
```
docker-compose up -d
docker-compose down
```

## Enter the Container
```
docker exec -i -t loom-ubuntu-docker /bin/bash
```
