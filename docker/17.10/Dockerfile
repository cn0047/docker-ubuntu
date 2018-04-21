FROM ubuntu:17.10

MAINTAINER Vladimir Kovpak <cn007b@gmail.com>

ENV TERM xterm

RUN apt-get update --fix-missing

RUN apt-get install -y vim
RUN apt-get install -y git colordiff
RUN apt-get install -y curl net-tools telnet
RUN apt-get install -y unzip
RUN apt-get install -y libpcre3-dev

# ApacheBench
RUN apt-get install -y apache2-utils

# ZeroMQ
RUN apt-get install -y libzmq5 libzmq5-dev 
