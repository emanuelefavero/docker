# Docker

Docker is a platform for developers and sysadmins to develop, deploy, and run applications with containers. The use of Linux containers to deploy applications is called containerization. Containers are not new, but their use for easily deploying applications is.

### Reasons why code brakes on different machines

1. One or more files missing
2. Software version mismatch
3. Different configuration settings (like different .env variables)

### docker benefits

1. Docker creates a container which is a virtual environment that contains all the files and software needed to run the application.
2. It will add all the versions of the software needed to run the application.

3. If your app works on your machine it will work on any machine with docker installed.

4. Is someone want s to join your project they can just run the docker container and start working on the project right away without configuring anything.

5. With docker we don't have to worry about deleting an application and accidentally removing dependencies needed by other applications.

## What is a container?

An isolated environment for running an application

### Container vs Virtual Machine

A virtual machine is different from a container in that a virtual machine runs a full-blown “guest” operating system with virtual access to host resources through a hypervisor. A container runs a discrete process, taking no more memory than any other executable, making it lightweight.

### hypervisor

A hypervisor is a piece of software, firmware or hardware that creates and runs virtual machines. A computer on which a hypervisor runs one or more virtual machines is called a host machine, and each virtual machine is called a guest machine.

NOTE: _VirtualBox_ is a hypervisor.

### Problems of virtual machines

- Each VM needs a full blown OS
- Slow to start
- Resource intensive

### What containers solve

- Allow running multiple apps in isolation
- Are lightweight
- USe OS of the host
- Start quickly
- Need less hardware resources

## Docker architecture

Docker uses a client server architecture. The Docker client talks to the Docker engine (daemon), which does the heavy lifting of building, running, and distributing your Docker containers. The Docker client and daemon can run on the same system, or you can connect a Docker client to a remote Docker daemon.
