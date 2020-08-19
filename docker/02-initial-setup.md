# Imagem no Docker

Será configurado um banco de dados (Postgres) no docker.
Primeiramente, procure no Docker Hub a imagem do postgres e cheque as necessidades para utilizar a imagem.

A primeira porta é referente ao SO e a segunda é utilizada no container.
```
docker run --name gostack_postgres -e POSTGRES_PASSWORD=docker -p 5434:5432 -d postgres
```

Execute a linha abaixo para listar containers em execução
```
docker ps
```
ou, para listar todos os containers
```
docker ps -a
```

Para inicializar um container, utilize o comando
```
docker start containerID
```