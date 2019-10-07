# Docker Node MongoDB Example

> Simple example of a dockerized Node/Mongo app

## Quick Start

```bash
# Run in terminal for ubuntu
# For removing older docker version
sudo apt-get remove docker docker-engine docker.io containerd runc

# Install docker using the convenience script
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh

# List of important docker cli commands

# List Docker CLI commands
docker
docker container --help

# Display Docker version and info
docker --version
docker version
docker info

# Execute Docker image
docker run hello-world

# List Docker images
docker image ls

# List Docker containers (running, all, all in quiet mode)
docker container ls
docker container ls --all
docker container ls -aq

# Take clone of this repo and goto that directory
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
