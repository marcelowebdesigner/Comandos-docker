# Guía de Comandos Docker Más Utilizados

![Docker Logo](./images/docker.svg)

## Gestión de Imágenes 

- `docker pull <image_name>`: Descarga una imagen desde Docker Hub.
- `docker images`: Lista todas las imágenes descargadas.
- `docker rmi <image_id>`: Elimina una imagen por su ID.

## Gestión de Contenedores

- `docker run -d -p <host_port>:<container_port> --name <container_name> <image_name>`: Ejecuta un contenedor en segundo plano con un puerto mapeado.
- `docker ps`: Lista los contenedores en ejecución.
- `docker ps -a`: Lista todos los contenedores, incluidos los detenidos.
- `docker stop <container_id>`: Detiene un contenedor.
- `docker start <container_id>`: Inicia un contenedor detenido.
- `docker rm <container_id>`: Elimina un contenedor por su ID.
- `docker logs <container_id>`: Muestra los logs de un contenedor.
- `docker exec -it <container_id> /bin/bash`: Abre una terminal interactiva dentro de un contenedor en ejecución.

## Volúmenes

- `docker volume create <volume_name>`: Crea un nuevo volumen.
- `docker volume ls`: Lista todos los volúmenes.
- `docker volume rm <volume_name>`: Elimina un volumen.

## Redes

- `docker network create <network_name>`: Crea una nueva red.
- `docker network ls`: Lista todas las redes.
- `docker network rm <network_name>`: Elimina una red.

## Docker Compose

- `docker-compose up`: Inicia todos los servicios definidos en el archivo `docker-compose.yml`.
- `docker-compose down`: Detiene y elimina todos los contenedores definidos en el archivo `docker-compose.yml`.
- `docker-compose logs`: Muestra los logs de todos los servicios.

## Información del Sistema

- `docker info`: Muestra información detallada sobre el sistema Docker.
- `docker version`: Muestra la versión de Docker instalada.

# Recursos Adicionales

Para aprender más sobre Docker, puedes consultar los siguientes recursos:

- [Documentación oficial de Docker](https://docs.docker.com)
- [Docker Hub](https://hub.docker.com)
- [Play with Docker](https://labs.play-with-docker.com/)
