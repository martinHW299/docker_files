# Docker file configurations

## Description
This repository contains Docker ...file and ...compose files for service configuration.

## Commands
```bash
docker compose -f docker-compose.yaml up
```
- Run in detach mode
```bash
docker compose up -d
```
```bash
docker compose stop
docker compose start
```
- Containers list
```bash
docker ps
```
- Get into container bash console
```bash
docker exec -it ${CONTAINER ID} bash
```

