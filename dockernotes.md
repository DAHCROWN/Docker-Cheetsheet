# Docker Terminal Commands

## Basic Commands

- `docker --version`
- `docker info`
- `docker help`

## Image Management

- `docker pull <image>`
- `docker images` lists the images that exist locally
- `docker rmi <image>`

## Container Management

- `docker run <image>`
- `docker run -- name <prefered_name> <image>`
- `docker run -d <image>` starts the images in the background
- `docker run -d -p <public_port>:<cont_port> <image>` starts the images in the background
- `docker ps` lists the running containers
- `docker ps -a` lists all the containers including closed sessions
- `docker logs <container-id>`
- `docker stop <container>`
- `docker kill <container>`
- `docker start <container>`
- `docker rm <container>`

## Building Images

- `docker build -t <name> .`
- `docker build -t <name>:<tag> .`

## Networks & Volumes

- `docker network ls`
- `docker volume ls`

---

# Definitions & Terminologies

## Image

The blueprint describing how that service is run,including the tools and microservices associated with it

## Container

A running instance of an image

## Volume

_Write your definition here._

## Network

_Write your definition here._

## Dockerfile KEYWORDS

- `FROM`
- `COPY`
- `RUN`
- `EXPOSE`
- `WORKDIR`
- `CMD` for the main and last command
- `LABEL` adds metadata e.g LABEL description='', LABEL version="1.0"

## FILES NAMES

Dockerfile
.dockerignore
