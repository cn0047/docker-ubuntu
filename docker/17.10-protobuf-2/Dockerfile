FROM cn007b/ubuntu:17.10

MAINTAINER Vladimir Kovpak <cn007b@gmail.com>

# protobuf 2
RUN curl -OL https://github.com/google/protobuf/releases/download/v2.6.1/protobuf-2.6.1.tar.gz \
    && tar xzf protobuf-2.6.1.tar.gz \
    && cd protobuf-2.6.1 \
    && apt-get update && apt-get install -y build-essential \
    && ./configure && make && make install \
    && ldconfig \
    && cd - && rm protobuf-2.6.1.tar.gz && rm -rf protobuf-2.6.1
