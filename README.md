## Ubuntu for DEVELOPMENT.

![Docker Image CI](https://github.com/cn007b/docker-ubuntu/workflows/Docker%20Image%20CI/badge.svg?branch=master)
[![Docker Build Status](https://img.shields.io/docker/build/cn007b/ubuntu.svg)](https://hub.docker.com/r/cn007b/ubuntu/)
[![Docker Automated build](https://img.shields.io/docker/automated/cn007b/ubuntu.svg)](https://hub.docker.com/r/cn007b/ubuntu/)
[![Docker Pulls](https://img.shields.io/docker/pulls/cn007b/ubuntu.svg)](https://hub.docker.com/r/cn007b/ubuntu/)

This image contains pre-installed tools helpful for development purposes.

# List of installed tools:

* tree, mc
* git, colordiff
* curl, telnet, ftp
* unzip
* make
* uuid

* docker, awscli

* apache bench

* dstat, sysstat

# Usage:

````sh
docker run -ti --rm -v $PWD:/app -w /app cn007b/ubuntu sh -c 'echo ok'

# or
docker run -ti --rm -v $PWD:/app -w /app cn007b/ubuntu /bin/bash
````
