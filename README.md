# docker-compose-wordpress
Docker compose utilizado para subir um ambiente wordpress

## Prerequesites
- Docker Engine
- Docker Compose
- Linux OS

## How to run

1. Build Apache Image in terminal

``docker build -t vinicius/apache ./Apache``

2. Run Docker Compose in terminal

``docker compose up -d``

1. Find your machine ip address in terminal

``docker inspect apache-site | grep IPAddress``

1. Access site on browser
``URL: <container_ip>``





