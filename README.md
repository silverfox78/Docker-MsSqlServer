# Docker-MsSqlServer

> Ejemplo de Docker-compose para disponer de una DB Sql Server 

![MS Sql Server](logo.png)

## TL:DR

> https://samuelbarrerabastidas.medium.com/ms-sql-server-con-docker-compose-2a3213266be3

## Imagenes oficiales de Sql Server

> https://hub.docker.com/_/microsoft-mssql-server

## Repositorio Github

> https://github.com/silverfox78/Docker-MsSqlServer.git

```sh
git init --initial-branch=main
git add .
git commit -am "Docker-Compose SqlServer - Ejemplo practico"
git remote add origin https://github.com/silverfox78/Docker-MsSqlServer.git
git pull --rebase origin main
git push origin main
```

## Identificacion

| Dato     | Valor         |
| -------- | ------------- |
| hostname | localhost     |
| port     | 1433          |
| dbname   | master        |
| user     | sa            |
| pass     | Password12345 |

## Validar version docker-compose

```sh
docker-compose --version
```

## Acciones

### Levantar la imagen

```sh
docker-compose up -d
```

### Detener la imagen

```sh
docker-compose stop
```

### Borrar la imagen (y lo que conlleva)

```sh
docker-compose down
```

## Consultar archivo local

```sh
cd /usr/shared/ && ls && cat hello.txt | nl
```
