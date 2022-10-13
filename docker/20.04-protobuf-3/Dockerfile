FROM cn007b/ubuntu:20.04

MAINTAINER V.K. <cn007b@gmail.com>

# protobuf 3
RUN curl -OL https://github.com/google/protobuf/releases/download/v3.11.4/protoc-3.11.4-linux-x86_64.zip \
    && unzip protoc-3.11.4-linux-x86_64.zip -d protoc3 \
    && mv protoc3/bin/* /usr/local/bin/ \
    && mv protoc3/include/* /usr/local/include/ \
    && chown $(whoami) /usr/local/bin/protoc \
    && chown -R $(whoami) /usr/local/include/google \
    && rm protoc-3.11.4-linux-x86_64.zip
