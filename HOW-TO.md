# HOW TO DOCKERIZE A NODE.JS APP

_NOTE: Remember to install and start docker in your machine before running any of the commands below._

## Create a node.js app

- app.js

## Create a Dockerfile

Create a file named `Dockerfile` in the root of your project. This file will contain all the instructions to build your image.

```dockerfile
FROM node:alpine
COPY . /app
WORKDIR /app
CMD node app.js
```

## Build the image

```bash
docker build -t IMAGE-NAME .
```

## Run the image

```bash
docker run IMAGE-NAME
```

## Login to docker hub

```bash
docker login
```

## Push the image to Docker Hub

```bash
docker push IMAGE-NAME
```

## Add a tag to the image

```bash
docker tag IMAGE-NAME USERNAME/IMAGE-NAME
```

## Pull the image from Docker Hub

```bash
docker pull USERNAME/IMAGE-NAME
```

## Remove a docker image

```bash
docker image rm IMAGE-NAME
```

## See a list of running containers

```bash
docker ps
```

## See a list of containers that have been stopped

```bash
docker ps -a
```

## Start a container and interact with it

```bash
docker run -it IMAGE-NAME
```
