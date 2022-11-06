# Docker Terminal commands

NOTE: _Always remember to start docker in your machine (by opening the docker app before running any of the commands below._

`docker version` - show docker version
`docker help` - show docker help
`docker info` - show docker info
`docker build -t <image-name> .` - build docker image
`docker images` - show docker images
`docker run <image-name>` - run docker image
`docker login` - login to docker hub
`docker push <image-name>` - push docker image to docker hub
`docker tag <image-name> <username>/<image-name>` - add tag to docker image
`docker pull <username>/<image-name>` - pull docker image from docker hub
`docker image rm <image-name>` - remove docker image
`docker ps` - show running docker containers
`docker ps -a` - show all docker containers
`docker stop <container-id>` - stop docker container
`docker run -it <image-name>` - start docker container and interact with it
`docker run -d <image-name>` - start docker container in detached mode
`docker run -p <host-port>:<container-port> <image-name>` - start docker container and map ports
`docker run -v <host-dir>:<container-dir> <image-name>` - start docker container and map volumes
`docker run -e <env-var>=<value> <image-name>` - start docker container and set environment variables
