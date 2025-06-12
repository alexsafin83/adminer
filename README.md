# Adminer
Adminer SQL database manager

## 1. How to use
### 1.1 Start/stop container
```
$ docker compose -f ./docker/docker-compose.dev.yaml up -d

$ docker compose -f ./docker/docker-compose.dev.yaml down
```

## 2. General usage
Open in your browser: http://localhost:8080 (the port on the left side of port mapping in docker-compose.yaml)

## 3. Configuration
### 3.1 Ports
You can change the port in docker-compose.yaml (the one on the left side).\
Usually you need to change this when running multiple containers at the same time.