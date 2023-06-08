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

``docker compose up``

1. Find your machine ip address in terminal

``docker inspect apache-site``

1. Connect to it via browser 

``<container_ip>:8080``





