FROM ubuntu:18.04

MAINTAINER Vladimir Kovpak <cn007b@gmail.com>

ENV TERM xterm

RUN apt-get update --fix-missing

RUN apt-get install -y vim tree mc
RUN apt-get install -y git colordiff
RUN apt-get install -y curl net-tools telnet ftp
RUN apt-get install -y unzip
# RUN apt-get install -y libpcre3-dev
RUN apt-get install -y make
RUN apt-get update --fix-missing && apt-get install -y lsb-core
RUN apt-get install -y uuid
RUN apt-get install -y nmap

# ApacheBench
RUN apt-get install -y apache2-utils

# ZeroMQ
RUN apt-get install -y libzmq5 libzmq5-dev

# Monitoring
RUN apt-get install -y dstat
RUN apt-get install -y sysstat
# RUN apt-get install -y iotop
RUN apt-get install -y cbm
