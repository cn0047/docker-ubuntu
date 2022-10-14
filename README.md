## Ubuntu for DEVELOPMENT.

[![Docker Image CI](https://github.com/cn007b/docker-ubuntu/workflows/Docker%20Image%20CI/badge.svg?branch=master)](https://github.com/cn007b/docker-ubuntu/actions)
[![Docker Automated build](https://img.shields.io/docker/automated/cn007b/ubuntu.svg)](https://hub.docker.com/r/cn007b/ubuntu/)
[![Docker Pulls](https://img.shields.io/docker/pulls/cn007b/ubuntu.svg)](https://hub.docker.com/r/cn007b/ubuntu/)

This image contains pre-installed tools helpful for development purposes.

# List of installed tools:

* vim, mc, tree, screen,
* git, colordiff,
* curl, wget, telnet, ftp,
* zip, unzip,
* make,
* uuid, jq,

* docker, awscli,

* apache bench,

* dstat, sysstat,

* and more.

# Usage:

````sh
docker run -ti --rm -v $PWD:/app -w /app cn007b/ubuntu sh -c 'echo ok'

# or
docker run -ti --rm -v $PWD:/app -w /app cn007b/ubuntu /bin/bash
````
