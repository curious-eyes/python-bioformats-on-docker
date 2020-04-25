FROM adoptopenjdk/openjdk8:jdk8u-ubuntu-nightly-slim

RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -q -y python3 python3-dev python3-pip

RUN pip3 install --upgrade pip requests

WORKDIR /app
